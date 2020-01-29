# EmplManagerBackEnd

Simple NodeJs backend service for retrieving
employees by position

## Setup

The project requires npm and nodeJs installerd

### Build Project

1. Install typescript: `npm install -g typescript`
2. Install npx: `npm install npx`
3. Install project dependencies: `npm install`

## Launch Server

1. `npx ts-node src/Server.ts`
2. Check localhos at port[8080](http://localhost:8080)

## Services:

| Position | Url |
|----------|-----|
|All Employees    | http://localhost:8080/allemployees  |
|Juniors          | http://localhost:8080/juniors       |
|Programmers      | http://localhost:8080/programmers   |
|Experts          | http://localhost:8080/engineers     |
|Managers         | http://localhost:8080/managers      |
|Admins           | http://localhost:8080/admins        |
|Nonadmins        | http://localhost:8080/nonadmins     |