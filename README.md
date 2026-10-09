# Study Assistant — starter

A starter repository for the CSC10014 Smart Virtual Assistant project.

## Setup

Execute the following commands in a Git Bash terminal to initialize the environment:
1. `python -m venv .venv`
2. `source .venv/Scripts/activate`
3. `pip install -e .`

## Run

`python -m assistant "where is the library?"`
-> Library: room B.201, open Mon-Sat 07:00-20:00.

## Test

`pytest -q` # -> 4 passed

## Project structure

- "No module named assistant" -> you forgot `pip install -e .` or the venv is not active.
- PowerShell blocks Activate.ps1 -> Set-ExecutionPolicy -Scope CurrentUser RemoteSigned

