>>>>>    Folder Sturucture
{
    main/
├── files/         ← your static course pages (HTML, CSS, JS)
├──                ← where you'll set up live-server locally
└── package.json
}

>>>>>    now in (main) folder run these
{
    npm init -y
    npm install live-server --save-dev
}

>>>>>    edit (package.json) file in (main) folder
{
    "scripts": {
  "start": "live-server pages --port=3000"}
}

>>>>>    to start live-server run this in (main) folder
{
    npm start
}