##### Equation Generator:

**Description**

Core functionality for generating equations.

**Contains**

- `good_equation_generator(highest_degree, highest_terms, equations)`
- `make_system_of_equations_consistent(equation_list)`
- `simple_equation_generator(eqn_degree, terms, equations)`
- `show(equation_list)`

**Documentation**

`good_equation_generator(highest_degree, highest_terms, equations)`

| Arguments        | Description                                                  |
| ---------------- | ------------------------------------------------------------ |
| `highest_degree` | Generates equations up to the bound degree specified         |
| `highest_terms`  | The highest number of monomials, excluding 1, to be had in each equation |
| `equations`      | The number of equations to generate                          |

- Returns: A list of equations.

`make_system_of_equations_consistent(equation_list)`

| Arguments       | Description                          |
| --------------- | ------------------------------------ |
| `equation_list` | The equation list to make consistent |

*Note that there is no guarantee of the equations being consistent by this algorithm. The number of equations generated must be sufficiently large to ensure a unique solution.*

- Returns: A list of consistent equations.

`simple_equation_generator(eqn_degree, terms, equations)`

| Arguments    | Description                                                  |
| ------------ | ------------------------------------------------------------ |
| `eqn_degree` | Generates equations up to the bound degree specified         |
| `terms`      | The highest number of monomials, excluding 1, to be had in each equation |
| `equations`  | The number of equations to generate                          |

- Returns: A list of consistent equations.

`show(equation_list)`

| Arguments       | Description               |
| --------------- | ------------------------- |
| `equation_list` | The equation list to show |

- Returns: void

