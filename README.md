# Infinite Re-renders in React useEffect Hook

This repository demonstrates a common React bug: infinite re-renders caused by a missing dependency array in the `useEffect` hook.  The `useEffect` hook, without a dependency array, runs after every render, leading to an infinite loop. This example shows how to fix it by providing the correct dependencies.