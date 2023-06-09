<h2><mark>React LifeCycle Methods Diagram</mark></h2>

<img src="https://i.ibb.co/QNVkmHC/react-functional-lifecycle.png" alt="functional component lifecycle">

<hr>

<h2> React functional component lifecycle methods</h2>

    1. Mounting
        - useState and useEffect are called during the mounting phase.
        - useState sets the initial state of the component.
        - useEffect is used to perform any side effects after the component has mounted.

    2. Updating
        - Whenever the component state or props change, the component re-renders.
        - During the updating phase, useEffect is called again.
        - Any changes to the state or props can be handled here.

    3. Unmounting
        - When the component is removed from the DOM, useEffect can be used for cleanup operations.
        - The cleanup function is called right before the component is unmounted.

    **Note: The lifecycle diagram above applies to functional components that use hooks. Without hooks, the lifecycle is simpler and does not have a separate phase for useEffect.**


