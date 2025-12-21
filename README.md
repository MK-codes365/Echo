# Echo

#### A simple, no distractions Chat App, meant to run straight from the terminal 

Echo is a terminal-user-interface (TUI) chat application for lightweight and fast chatting, to be run directly from the terminal - no switching to an ugly , counterintuitive GUI based app running on a browser or a webapplet


### Tech Stack 

#### Server 
    - Node.js + Express 
    - Mongoose + MongoDB Atlas 

#### Client 
    - Go + Bubbletea
    
#### Database 
    - MongoDB Atlas 
        - Users
        - Messages 

#### Base Project Structure 

```
Echo/
├── CONTRIBUTING.md           -> Guidelines
├── README.md                 -> Project Overview
│ 
├── client                    -> Client Application Code
│ 
├── contributors              -> Contributor Records
│   
└── server                    -> Chat Server + Backend 
```

> this README will be updated accordingly.
### Quick Start 
Before starting - check out our [CONTRIBUTING.md](https://github.com/opencodeiiita/Echo/blob/main/CONTRIBUTING.md) to get a refresher on contribution and general workflow.

#### Project Setup:

After forking and cloning the project, install the following dependencies:
    
- NodeJs [Download](https://nodejs.org/en)
    

- Within `/server` 
```bash 
npm install npm install express ws cors
npm install --save-dev nodemon
```

- Within `/client`
```bash 
go get github.com/charmbracelet/bubbletea
go get github.com/gorilla/websocket
```

### Contact 
Reach out to me via Discord, ID: Washikiballa-San
