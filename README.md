npm install

to run the dashboard in development:
npm run dev

to generate production build "out" folder:
npm run export


To Deploy to dvb:
Open file .ui5deployrc and adjust the request number

` "transportNo": "DVBK9A21TR", `

run the buid/export process by running the following command:

`npm run export`

 then run the following command:

`npm run deployer -- --user MIRAJSM --pwd Abc123`

and adjust your your username/password.
