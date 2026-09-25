# Project to learn go lang

https://www.youtube.com/watch?v=gXmznGEW9vo

## CLI To-Do List Application

A command-line tool for managing tasks directly in your terminal.

Goals:

- Read/write data to filesystem: Start with the built-in CSV library for simplicity.
- Printing Tabular Data: Use the text/tabwriter package for clean, aligned console output.
- CLI app with multiple commands: Implement commands like add, list, complete, and delete.

Good to have:

- Support for optional due dates when creating tasks.
- Migrating from CSV to SQLite for more robust data management.

## Stateless Web API

A backend calculator service designed to practice standard web development patterns.

Goals:

- Stateless API: Focus on implementation without needing a persistent database.
- Standard Library: Use net/http to understand Go's core idioms.
- Data Validation: Ensure incoming requests meet expected parameters.
- Middleware: Add custom logging for request tracking.

Good to have:

- Support for operations like addition, subtraction, multiplication, and division.

## Dead Link Web Scraper 

A tool to recursively scan websites and detect broken or dead links.

Goals:

- Recursive Scanning: Crawl pages to find and validate links.
- Status Code Checking: Identify dead links (400 or 500 status codes).
- Standard Packages: Utilize net/http for requests and net/html for parsing.

Good to have:

- Implement concurrency with goroutines and channels for faster scraping.
- Handle edge cases like redirects and staying within domain boundaries.

## URL Shortener Website

A web application that takes long URLs and provides shortened, redirectable versions.

Goals:

- Templating: Use html/template to render dynamic web pages.
- HTTP Redirects: Master 301 or 302 status codes to forward traffic.
- Error Handling: Gracefully manage missing URLs with a 404 page.

Good to have:

- Integrate a simple database to persist the URL mappings.

## Currency Converter TUI

An interactive terminal-based user interface for real-time currency conversion.

Goals:

- TUI Development: Create an interactive form using the Bubble Tea (huh) library.
- Third-party API: Fetch exchange rates from services like Open Exchange Rates.
- Secret Management: Securely handle API tokens using environment variables.

Good to have:

- Add a persistent configuration file for user preferences.
