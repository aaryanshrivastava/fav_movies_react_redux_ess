Redux is a Js tool to manage state of our application.
Being a Js app we can use it with any js application be it Vue, Angular, etc.
It's an predictable state management tool.Helps to write consistent application.
Redux provides us with store to keep all states at one place, so that any component can access it any time.

State is an updatable structure that is used to contain data or information about the component and can change over time. The change in state can happen as a response to user action or system event. It is the heart of the react component which determines the behavior of the component and how it will render.
On the other hand, props are read-only components.It allows passing data from one component to other components. Props are immutable so we cannot modify the props from inside the component.In general, props are used to pass data from a parent component to a child component, while state is used to store and manage data within a single component. This allows the component to control its own behavior and state, and makes it more reusable in different contexts.

Redux principles :
1 Single source of truth.
2 State is read only.
3 Changes to the state can be made by pure functions only.(Pure functions ~ Reducers)

Benefits :
1 Predictable
2 Easy to Maintain
3 Persitance of data

Working :
UI -> Action -> Reducer -> Store -> UI.

Actions only describe what happened, but don't describe how the application's state changes. Reducer specifies how the application's state changes in response to actions sent to the store.

For Hooks->
The state of each component is completely independent. Hooks are a way to reuse stateful logic, not state itself. In fact, each call to a Hook has a completely isolated state. So, you can even use the same custom Hook twice in one component.
The equivalent of componentDidMount in hooks is the useEffect function. Functions passed to useEffect are executed on every component rendering, unless you pass a second argument to it.
