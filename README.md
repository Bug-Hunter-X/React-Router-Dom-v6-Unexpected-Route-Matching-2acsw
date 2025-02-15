This repository demonstrates a subtle bug in React Router DOM v6 concerning unexpected route matching. The bug manifests as incorrect route resolution, leading to unintended navigation to the catch-all route.  The solution involves careful consideration of route order and potentially using `useLocation` for more complex scenarios.  The `bug.js` file showcases the problematic code, while `bugSolution.js` provides a corrected implementation.