# Set up a Playwright MCP server

Youtube video from task 1: `2 minutes to set up a local Puppeteer MCP Server` is ok, but since then, [it has been archived](https://github.com/modelcontextprotocol/servers-archived/blob/9be4674d1ddf8c469e6461a27a337eeb65f76c2e/src/puppeteer/README.md#L4). My main concern is that is an un-mantained repo with over a year so I asked my bestie ChatGPT for an option and I was re-directed to playwright. 

<img width="934" height="296" alt="image" src="https://github.com/user-attachments/assets/db0cbb05-4499-47f2-b15a-c98aac3a083f" />

Playwright is Microsoft’s open-source browser automation framework; the repo uses the Apache 2.0 license. Note than an LLM will probably consume more tokens as it has to call a tool, then receive tool results, snapshots, extracted text etc. A normal flow looks like:

Your prompt
  ↓
LLM thinks and decides to call Playwright
  ↓
MCP client sends command to Playwright MCP
  ↓
Playwright opens/clicks/reads page locally
  ↓
Result goes back to the LLM

## Step-by-step

1. In Settings / Advanced Settings, select Model Context Protocol. Once it loads, select the button 🛜 that says `Setup MCP Connector`

   <img width="959" height="1080" alt="Screenshot_20260709_015125" src="https://github.com/user-attachments/assets/187b397b-561e-434f-8473-e8b9b3976fa4" />

2. Now, a security disclaimer, I do think you would generally wont want to run mcp's locally, specially under an enterprise or proffessional environment, but since Im just evaluating and will disable this after test -yolo, I will select to install on `This Device`. Think it through if you decide to "live" with this setup.

    <img width="533" height="519" alt="image" src="https://github.com/user-attachments/assets/5b910c4f-5947-42cd-98fe-9fdd994c83f1" />

3. Copy the node command and execute.

   <img width="633" height="603" alt="image" src="https://github.com/user-attachments/assets/0fe753fa-f023-4b7f-ae57-85295a53c51a" />

4. Once the npx command is done, you will see a `server ready` msg, clik on `Get started`. With this, you have create a local mcp server.
   
   <img width="540" height="484" alt="image" src="https://github.com/user-attachments/assets/cc339cd7-9d5c-44d7-b43f-341b4fa7936c" />

5. `Edit Servers` you will now set up the mcp server directly from Playwright's repo [here](https://github.com/microsoft/playwright/blob/2af5f0e31e298ed2b399c5e87d2f25336496946e/docs/src/getting-started-mcp.md#L4).

   <img width="693" height="170" alt="image" src="https://github.com/user-attachments/assets/b3d08b48-2a4f-4213-a8fa-0759760f889e" />

6. Look up for the values in repo, then paste and clik `Save Changes`
   
   <img width="571" height="462" alt="image" src="https://github.com/user-attachments/assets/a1c930e1-8e1f-4fdb-bd6a-b5bc755579fe" />

7. This means you are ready

   <img width="579" height="238" alt="image" src="https://github.com/user-attachments/assets/c9859169-4811-43b6-aa23-ab0dcb71e955" />

8. We are testing with a simple prompt, using the newly released Grok 4.5. I'm really rooting for this model, and I hope this statement does not age bad.

   <img width="785" height="996" alt="image" src="https://github.com/user-attachments/assets/d457eef1-0c05-4434-86af-dbdc2a932918" />

9. For this test, I only enabled the Playwright MCP

    <img width="375" height="594" alt="image" src="https://github.com/user-attachments/assets/fbf1edb8-e060-4665-abfd-03a54728f6c8" />

10. This is the output

    <img width="625" height="957" alt="Screenshot_20260709_021020" src="https://github.com/user-attachments/assets/ff07189a-6d47-4587-9e7a-10852b1a154c" />

11. And this is how the HN portal looked

    <img width="693" height="703" alt="Screenshot_20260709_021239" src="https://github.com/user-attachments/assets/9c1eb827-249e-4d1c-a590-a9e7fdfb47be" />

12. Approximate cost and usage per TypingMind

    <img width="539" height="744" alt="image" src="https://github.com/user-attachments/assets/d6ac40e4-88fd-4fcb-bade-fbb79c84bd09" />

## Conclusions

At the end we achieved the same but with other product. Process is Simple and straightforward. 8 out of 10 because the process is good but nothing special.

Will I be using this next week? yes, I sometimes like to take notes to save them in my obsidian setup on whatever im learning or expand on a subjet and this can help as vision is not required. If you will be doing documentation, this can help you achieve those tasks, specially for long running boring tasks. 

