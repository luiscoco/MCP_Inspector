# MCP Inspector (Model Context  Protocol Inspector)

For more information about MCP Inspector visit the official site:

https://github.com/modelcontextprotocol/inspector/tree/main

## 1. What is MCP Inspector

The MCP inspector is a developer tool for **testing** and **debugging** **MCP servers**.

The inspector runs both a **MCP Client** UI (default port **5173**) and an **MCP proxy Server** (default port **3000**). Open the client UI in your browser to use the inspector. 

## 2. How to Download the MCP Inspector Github repo

We download the ZIP github repo file

![image](https://github.com/user-attachments/assets/450b8744-7d29-40ee-97af-8dc8860fe623)

We uncompress the MCP Inspector ZIP file in our local machine

![image](https://github.com/user-attachments/assets/34de8f27-4077-4112-b673-d35be49470ca)

## 3. How to Open MPC Inspector application with VSCode

We navigate to the MCP Inspector location and we open with VSCode

![image](https://github.com/user-attachments/assets/b60b75b9-73ba-45c2-a322-98ce8945b4cf)

## 4. How to Install Packages 

We run the following command to intall the packages

```
npm i 
```

or 

```
npm install
```

![image](https://github.com/user-attachments/assets/4eb1bcbf-e447-4107-a20a-53fedf87e861)

## 5. How to Build and Run the MCP Inspector Client

We build and run the application executing the following commands:

```
npm run build
```

and

```
npm start
```

We confirm the MCP Client is running:

![image](https://github.com/user-attachments/assets/b23c1079-0794-40a4-a831-25e98e8cec67)

We open the referred web site:  **http://localhost:5173**

![image](https://github.com/user-attachments/assets/42eae47d-ef4c-4fd1-a286-af89d6ef46b4)

## 6. How to run a MCP Server and Send Requests

For example we are going to connect to the MCP Server provided by this NodeJS package:

https://www.npmjs.com/package/@modelcontextprotocol/server-everything

![image](https://github.com/user-attachments/assets/ae6b688b-d596-4f8a-9277-d10cf3b40d37)

We can launch and connect to the NodeJS MCP Server from the MCP Inspector Client

Transport Type:	**STDIO**

Command:	**npx**

Arguments:	**-y @modelcontextprotocol/server-everything**

![image](https://github.com/user-attachments/assets/d25435ae-6802-4c2d-805e-5ec8e73895c0)

When we are connected to the MCP Server we navigate to the Tools tab

![image](https://github.com/user-attachments/assets/20c6f815-cc35-4292-bd67-ecb856011135)

We visualize the available Tools

![image](https://github.com/user-attachments/assets/6b0d8fb4-5277-41c7-9358-20ba77bbabb1)

We select the "echo" tool and we send a command

![image](https://github.com/user-attachments/assets/d6c931ae-2a1c-49d3-8021-c80879c2dc92)

We receive the echo message response

![image](https://github.com/user-attachments/assets/e867c9d5-0b3b-4158-95d5-c64cd28641c3)
