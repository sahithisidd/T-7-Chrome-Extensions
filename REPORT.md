# Browser Extension Security Analysis

**Project Title:** Checking Browser Extensions for Security Risks  

---

## 1. Why This Project Was Done

Browser extensions are super handy they let us add new features to our browsers, like enabling copy-paste on blocked websites or working offline in Google Docs.  
But here’s the catch: the same power that makes them useful can also make them dangerous. A shady extension could track what we type, steal passwords, or insert unwanted ads without us even noticing.  

This project’s goal was simple: take a close look at every extension installed in the browser and make sure none of them are suspicious or harmful.

---

## 2. How the Check Was Done

1. **Looking at the Extensions**  
   - Opened the browser’s extension management page to see the full list of installed add-ons.  
   - Took screenshots for proof and record-keeping.

2. **Reviewing Each Extension**  
   - Checked the name, version, and publisher.  
   - Asked: “Did I install this myself?” and “Does it do something I actually use?”  
   - Looked for warning signs like:
     - Unknown publishers
     - Asking for too many permissions
     - Not matching its described purpose

3. **Classifying the Risk**  
   - **Safe:** From a trusted source, popular, and matches its purpose.  
   - **Suspicious:** Doesn’t look familiar or asks for too much access.  
   - **Malicious:** Confirmed security threat.

---

## 3. What Was Found

Here’s the list of extensions that were reviewed:

- Always active Window – Always Visible (v0.6.4)  
- Don’t F*** With Paste (v1.1)  
- Enable Copy Paste – ECP (v2.0.0.0)  
- Enable Copy/Paste (v1.0)  
- Google Docs Offline (v1.57.0)  
- McAfee® WebAdvisor (v8.1.0.467)  
- Microsoft Power Automate (v3.25.501)  
- Microsoft React Automation (v2.6.10)  
- Safer Chat with AI models (v5.1.0)  

**Verdict:**  
- All came from trusted sources like the Chrome Web Store or Microsoft Store.  
- No weird or unknown extensions popped up.  
- Security tools (like McAfee WebAdvisor) were present and functioning.  
- Productivity-related tools were legitimate and in use.

---

## 4. Conclusion

After going through each extension one by one:  
 * No dangerous or suspicious extensions were found.  
 * No immediate action is needed,everything installed is safe and useful.  

---

## 5. Good Practices Moving Forward

- Check extensions every few months to catch anything new or unwanted.  
- Keep them updated so they get the latest security fixes.  
- Avoid downloading extensions from random websites.  
- If you stop using an extension, remove it : less clutter, less risk.

---
