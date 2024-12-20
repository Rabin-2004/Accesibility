# Role, Name and Value

### In cases where we cannot use a semantically correct HTMl tags such as framework limitations, we can build a custom control using role, name and value for accesibility

# Key points:
- `<div role= 'button'> ABC </div>`. Here the role button states that this component is functioning as button and ABC is the name.

- In form components like select: `<select name='xyz'>....</select>.` The name attribute is not the accesible name. For such elements we use `<select aria-label= 'ABC' name = 'xyz'>` .

- Some states and components have values. An accordion has value to know if its expanded or not.
`<div aria-expanded= 'false'>` states that this component is not expanded. 