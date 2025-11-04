n8n RAG Chat Workflow
Ask questions about any Google Drive document using Pinecone + OpenAI.
How to Use
1. Import Workflow  
   → Click [this JSON file](my-rag-workflow.json) → Copy all  
   → In n8n: New → Import from Clipboard (or drag file)
   
3. Fix Red Warnings  
   - Add credentials:  
     - `Google Drive account`  
     - `OpenAi account`  
     - `PineconeApi account`  
   - Create Pinecone index: `test-index` (1536 dimensions)

4. Click "Test Workflow" → then "Chat"

Warning Fix Tips  
- Red warnings = missing credentials  
- Click any red node → "Select credential" → create new


Made by [Tahir khan](https://github.com/Tahirkhan-aiml)
