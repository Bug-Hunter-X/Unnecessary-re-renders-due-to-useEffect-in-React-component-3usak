# Unnecessary Re-renders in React useEffect Hook

This repository demonstrates a common React performance issue: unnecessary re-renders caused by an improperly used `useEffect` hook.  The original code triggers the effect after every render, leading to excessive logging and potential performance problems. The solution showcases how to optimize the effect to prevent unnecessary re-renders.