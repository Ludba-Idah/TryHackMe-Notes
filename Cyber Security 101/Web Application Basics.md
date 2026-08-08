# 🔗 Room: How Websites Work

**Category:** Fundamentals

## Overview

This room covers the architecture of web applications, how URLs guide browsers, how clients and servers communicate via HTTP, and the security headers that keep traffic safe.

## Core Concepts

Web Architecture

*   `Front End` -> It is the browser-facing surface built with HTML, CSS, and JavaScript.
*   `Back End` -> It is the server, database, and infrastructure processing the requests.

Anatomy of a URL

*   `Scheme` -> The protocol used for access (e.g., HTTPS).
*   `Domain` -> The unique name of the website (e.g., tryhackme.com).
*   `Port` -> The doorway used for communication (e.g., 443 for HTTPS).
*   `Path` -> The exact file being requested on the server.

HTTP Methods & Status Codes

*   `GET` -> Request method used to view information.
*   `POST` -> Request method used to submit new data to the server.

*   `200 OK` -> Response code confirming the request was successful.
*   `404 Not Found` -> Response code indicating the requested resource doesn't exist.
*   `500 Internal Error` -> Response code indicating a crash on the server side.

## Security Headers

*   `CSP` -> Restricts where scripts can load from to prevent XSS attacks.
*   `HSTS` -> Forces the browser to strictly use encrypted HTTPS connections.
*   `X-Content-Type-Options` -> Prevents the browser from guessing file types.
