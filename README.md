# Next.js 15 app directory unexpected behavior

This repository demonstrates an unexpected behavior in Next.js 15's app directory.  A simple page, when deployed to the app directory, produces unexpected behavior (e.g., a blank page, incorrect rendering, or other deviations from expected output).  This issue is specific to the app directory and does not occur when using the pages directory.

## Steps to reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe the unexpected behavior.

## Expected behavior

The page should render a simple "Hello World!" message.

## Actual behavior

A blank page or another unexpected output is displayed.

## Possible causes

* A bug in Next.js 15's app directory implementation.
* An incorrect configuration.
* A conflict with other packages or dependencies.

## Solution

(This section is left blank, as the purpose of this issue is to highlight a problem for Next.js maintainers to fix.)