# Synchronisation MantisBT

[![License GPL 3.0](https://img.shields.io/badge/License-GPL%203.0-blue.svg)](https://github.com/itsmng/mantis/blob/main/LICENSE.md)
[![Project Status: Active](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)

Extend GLPI with Plugins.

## Table of Contents

* [Synopsis](#synopsis)
* [Features](#features)

## Synopsis

This plugin allows to synchronize tickets, problems and changes with the MantisBT tool.

### Features

* Connection via webservices of MantisBT (MantisConnect);
* Creation of a new MantisBT issue from a ticket, problem or GLPi change;
* Link an existing MantisBT issue from a ticket, problem or GLPi change;
* Transmission of information from the GLPi object to the created / linked MantisBT issue;
* Transfer and auto-update attachments of GLPi object to the MantisBT created / linked issue;
* Automatic update of GLPI object (transition to the resolved state) when the MantisBT issue is resolved;
* Management rights for the plugin;
* Configuration management of interconnection.
