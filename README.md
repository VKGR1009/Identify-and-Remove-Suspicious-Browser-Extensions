# Identify-and-Remove-Suspicious-Browser-Extensions
Browser Extensions Security Analysis

Objective  
The task involved reviewing installed browser extensions to identify suspicious or unused ones, evaluate their permissions, and remove any potential security risks.

Steps Performed  
1. Opened the browser’s extension manager.  
2. Reviewed each extension’s permissions and publisher details.  
3. Identified suspicious/unused extensions.  
4. Removed or disabled unnecessary extensions.  
5. Documented findings and best practices.  

Findings  
Extensions Removed:  
- Example: XYZ Ad Blocker – Unknown publisher, requested full access to browsing data.  
- Example: Free VPN – Potential data logging risk.  

Extensions Kept:  
- Example: Grammarly – Trusted publisher.  
- Example: uBlock Origin – Safe and widely used.  

Best Practices  
- Only install extensions from trusted sources.  
- Review permissions carefully before installing.  
- Regularly audit and remove unused extensions.  
- Keep browser and extensions updated.

### How to Audit Extensions Yourself

1. Open your browser and navigate to the extension management page:
   - **Chrome/Edge:** chrome://extensions/
   - **Firefox:** about:addons
2. Review each listed extension:
   - Note the publisher and user reviews.
   - Check the permissions requested (e.g., “Read and change all your data on all websites”).
3. For any extension you don’t recognize or trust:
   - Click **Remove** or **Disable**.
4. For trusted and widely used extensions, choose **Keep**.
5. Restart your browser and confirm behavior improved.

#### Extensions Removed
| Extension        | Concern                                                            |
|------------------|--------------------------------------------------------------------|
| Free VPN         | Unverified publisher, excessive permissions, potential data logger |
| XYZ Ad Blocker   | Unknown publisher, unnecessary full-site access                   |

#### Extensions Kept
- Grammarly (Trusted publisher)  
- uBlock Origin (Open-source and minimal permissions)

#### Future Enhancements
- Automate extension permission audits via script.  
- Cross-browser version of this analysis.  
- Dashboard to track safe and unsafe publishers/extensions.


