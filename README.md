# Next.js 15 App Router: Unexpected Behavior with Simple Functional Component

This repository demonstrates an unexpected behavior encountered when using a simple functional component in the `pages` directory of a Next.js 15 application using the App Router.

**Bug:**

A basic functional component, as shown in `bug.js`, does not render correctly when placed in the `pages` directory.  This might manifest as a blank page, an error, or unexpected behavior.  The expected behavior is for 'Hello, world!' to be displayed.

**Solution:**

The solution might involve refactoring the component to fit within the App Router's structure, potentially moving it to a different directory or converting it to a layout or page component that integrates correctly with the App Router's routing system. The corrected code is provided in `bugSolution.js`
