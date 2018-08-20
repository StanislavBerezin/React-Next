#passing PROPS
```function Person(props){
  return(
    <div class='person'>
      <h1>{props.name}</h1>
    
      </div>
  );
}
ReactDOM.render(<Person name ="Test"/>, document.querySelector("#p1"));```
