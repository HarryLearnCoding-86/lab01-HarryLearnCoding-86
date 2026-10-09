# Study Assistant — starter

A starter repository for the CSC10014 Smart Virtual Assistant project.

## Setup

(Lab 1): write the exact steps a new teammate needs, from a fresh machine to
running the app and the tests. Your partner will follow them without your help.

## Run

python -m assistant "where is the library?"
 # -> Library: room B.201, open Mon-Sat 07:00-20:00.

## Test

pytest -q # -> 4 passed

## Project structure

- "No module named assistant" -> you forgot `pip install -e .` or the venv is not active.
- PowerShell blocks Activate.ps1 -> Set-ExecutionPolicy -Scope CurrentUser RemoteSigned

