 CRUD:
 import { useState } from "react";

function App() {
  const [items, setItems] = useState(["Book", "Pen"]);
  const [text, setText] = useState("");

  // Add item
  const addItem = () => {
    if (text.trim() === "") return;
    setItems([...items, text]);
    setText("");
  };

  // Remove item
  const removeItem = (i) => {
    setItems(items.filter((_, index) => index !== i));
  };

  // Update item
  const updateItem = (i) => {
    const newValue = prompt("Enter new value:");
    if (!newValue) return;
    const newItems = [...items];
    newItems[i] = newValue;
    setItems(newItems);
  };

  return (
    <div style={{ padding: 20 }}>
      <h1>My React List</h1>

      <input
        value={text}
        onChange={(e) => setText(e.target.value)}
        placeholder="Add item"
      />
      <button onClick={addItem}>Add</button>

      <ul>
        {items.map((item, index) => (
          <li key={index}>
            {item} &nbsp;
            <button onClick={() => updateItem(index)}>Update</button>
            <button onClick={() => removeItem(index)}>Delete</button>
          </li>
        ))}
      </ul>
    </div>
  );
}

2/List: function List()
{
     const frust=[{id:1,name:"banan",calories:22},
                 {id:2,name:"apple",calories:220},
                {id:3,name:"orange",calories:222}];
const lowcal=frust.filter(frust => frust.calories >200);
 
const ListItems=lowcal.map(frust=><li key={frust.id}>{frust.name}&nbsp;:<b>{frust.calories}</b></li>);

    return(<ul>{ListItems}</ul>);
      
}
export default List;

3/ useState() hook :
if any funcion start with  use it's for sure react hooks,
import React, { useState } from "react";

/**
 * A profile component demonstrating basic state management 
 * for strings, numbers, and booleans.
 */
function hooks() {
  const [name, setName] = useState("Hammouti");
  const [age, setAge] = useState(0);
  const [isEmployed, setIsEmployed] = useState(true);

  // Updates the name to a specific value
  const handleUpdateName = () => {
    setName("Nouhaila");
  };

  // Increments age by 1
  const handleIncrementAge = () => {
    setAge((prevAge) => prevAge + 1);
  };

  // Toggles the employment status boolean
  const toggleEmployment = () => {
    setIsEmployed(!isEmployed);
  };

  return (
    <div style={{ padding: "20px", fontFamily: "Arial, sans-serif" }}>
      <h2>User Information</h2>
      
      <section>
        <p><strong>Name:</strong> {name}</p>
        <button onClick={handleUpdateName}>Update Name</button>
      </section>

      <section>
        <p><strong>Age:</strong> {age}</p>
        <button onClick={handleIncrementAge}>Increment Age</button>
      </section>

      <section>
        <p><strong>Employed:</strong> {isEmployed ? "Yes" : "No"}</p>
        <button onClick={toggleEmployment}>Toggle Status</button>
      </section>
    </div>
  );
}

export default UserProfile;import React, { useState } from "react";

/**
 * A profile component demonstrating basic state management 
 * for strings, numbers, and booleans.
 */
function UserProfile() {
  const [name, setName] = useState("Hammouti");
  const [age, setAge] = useState(0);
  const [isEmployed, setIsEmployed] = useState(true);

  // Updates the name to a specific value
  const handleUpdateName = () => {
    setName("Nouhaila");
  };

  // Increments age by 1
  const handleIncrementAge = () => {
    setAge((prevAge) => prevAge + 1);
  };

  // Toggles the employment status boolean
  const toggleEmployment = () => {
    setIsEmployed(!isEmployed);
  };

  return (
    <div style={{ padding: "20px", fontFamily: "Arial, sans-serif" }}>
      <h2>User Information</h2>
      
      <section>
        <p><strong>Name:</strong> {name}</p>
        <button onClick={handleUpdateName}>Update Name</button>
      </section>

      <section>
        <p><strong>Age:</strong> {age}</p>
        <button onClick={handleIncrementAge}>Increment Age</button>
      </section>

      <section>
        <p><strong>Employed:</strong> {isEmployed ? "Yes" : "No"}</p>
        <button onClick={toggleEmployment}>Toggle Status</button>
      </section>
    </div>
  );
}

export default hooks;

3/ import React, { useState } from "react";

/**
 * A sleek Counter component demonstrating 
 * increment, decrement, and reset logic.
 */
function Counter() {
  const [count, setCount] = useState(0);

  // Increase the count
  const handleIncrement = () => {
    setCount((prev) => prev + 1);
  };

  // Decrease the count
  const handleDecrement = () => {
    setCount((prev) => prev - 1);
  };

  // Reset to initial state
  const handleReset = () => {
    setCount(0);
  };

  return (
    <div style={{ textAlign: "center", marginTop: "50px" }}>
      <h2>Counter Application</h2>
      
      <p style={{ fontSize: "24px" }}>
        Current Count: <strong>{count}</strong>
      </p>

      <div style={{ display: "flex", gap: "10px", justifyContent: "center" }}>
        <button onClick={handleIncrement}>Add</button>
        <button onClick={handleDecrement}>Less</button>
        <button onClick={handleReset} style={{ color: "red" }}>
          Reset to 0
        </button>
      </div>
    </div>
  );
}

export default Counter;

export default App;
