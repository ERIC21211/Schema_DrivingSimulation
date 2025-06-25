# Schema_DrivingSimulation
Implementation of a schema that validates driving simulation data, exports data as json and csv and compatible with hashing and databases downstream

INSTALL THE NODE PACKAGE
npm init -y
npm install ajv ajv-formats fast-csv

COMMAND TO VALIDATESESSION FILE
node validateSession.js

COMMAND TO EXPORT SESSION DATA INTO CSV FILE
node exportSession.js


PROJECT UPDATED STRUCTURE
driving-simulator/
├── trip1.json
├── trip1.csv           <- Created by export script
├── session_schema.json
├── validateSession.js
├── exportSession.js
├── package.json
└── node_modules/


