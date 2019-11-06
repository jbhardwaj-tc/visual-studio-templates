## Introduction
This is a template to create a Windows Service in .Net Core 3.0

## Installation instructions
- Download and double click on the VSIX file
- Follow the instructions on the installer

## Usage
- Open visual studio 2019
- Create a new project
- Select 'Windows Service Dot Net Core 3.0" from the list of available templates and click 'Next'
- Choose your project location and name and click 'Create'

## Running the service
- Just hit F5 in visual studio and the service should launch in console mode.

## Installing the service on windows
- > sc create **servicename** binPath=**service_exe_full_path**
