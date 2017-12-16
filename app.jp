const express = require('express');
//const session = require("express-session");
const sass = require("node-sass");
const Twig = require("twig")

// environments
const SESSION_SECRET = process.env.AUTOMATA_SESSION_SECRET;
const DB_PATH = process.env.AUTOMATA_DB_PATH;

// settings
const app = express();
//app.use(session({ secret: SESSION_SECRET, resave: false, saveUninitialized: true, cookie: { maxAge: null, expires: false } }));
//app.use(bodyParser.urlencoded({ extended: false }));

// assets
/*
app.get("automata.css", function(req, res) {
  const f = sass.renderSync({file: __dirname + "/assets/index.css"});
  res.writeHead(200, {"Content-Type":"text/css"});
  res.end(f.css, "utf-8");
});*/

app.get("/", function(req, res) {
  res.render("index.twig");
});

app.listen(3000);
