⭐ STEP 1 — Create GitHub Personal Access Token (PAT)
✔ Open link:
https://github.com/settings/personal-access-tokens/new
✔ Choose:
•	Token Type: Fine-grained or Classic
•	Expiration: 30 days
•	Scopes Required:
o	repo (Read & Write)
✔ Copy your new PAT and save it temporarily.
📌 Screenshot 1 Placeholder: (Insert screenshot of token generation page)
 
⭐ STEP 2 — Store Token Securely in .env
Create a file in your Task-6 folder:
.env
GITHUB_MCP_PAT=your_token_here
📌 Screenshot 2 Placeholder: (Insert screenshot of .env file — blur token)

 

⭐ STEP 3 — Configure Gemini CLI to Use GitHub MCP Server
Open or create the file:
C:\Users<your-username>.gemini\settings.json
Paste the following configuration:
📌 Screenshot 3 Placeholder: (Insert screenshot of the settings.json file)
 
✔ Clean
✔ Official format
✔ Token auto-loads from .env
✔ Perfect for Hosted MCP

⭐ STEP 4 — Restart Gemini CLI
In terminal:
gemini logout
gemini login
If login cannot occur due to Gemini API key issues, you can still continue — Hosted MCP works without Gemini authentication.
________________________________________
⭐ STEP 5 — Verify MCP Connection
Run:
gemini mcp list
Expected Output:
github — Ready (40+ tools)
📌 Screenshot 4 Placeholder: (Insert screenshot of 'gemini mcp list' showing GitHub enabled)
 
⭐ STEP 6 — Test GitHub MCP Server
Ask Gemini:
List my GitHub repositories
If MCP is correctly connected, Gemini will respond with:
•	Repo names
•	Repo URLs
•	Public/private details
📌 Screenshot 5 Placeholder: (Insert screenshot of “List my GitHub repositories” output)
 


BY MUHAMMAD SHOAIB ABDUL SHAKOOR (00262018)
