Controlled-Treasury 

Description
This repository implements a smart contract for managing a controlled treasury, with built-in, flexible risk-management controls.

How to build and run tests

Build the treasury package

sui move build --path treasury


Run tests (in a separate package, using Move 2024 — requires a custom compiler build from main)

sui move test --path tests


Notes on testing

The tests are written in Move 2024, so you must use a version of the Move compiler built from the main branch.

The test suite and the treasury package are kept separate to isolate concerns.
