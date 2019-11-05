# CS 1C Group Project - 2D Graphics Modeler, Inc.
## Due The Week of December 9, 2019

See [Canvas](https://ivc.instructure.com/courses/29570/assignments/432581) for more details.

## Requirements:
- [x] 10 [User Stories](https://docs.google.com/document/d/11SipLutjPjCpkd7EqmDIZyedwFQUsqCJABHykVbEUrE/edit?usp=sharing)
### General:
- [ ] Exception Handlers
### Qt:
- [ ] Draw shapes on QWidget rendering area
- [ ] Use composition with QWidget class and Shape class
### Classes:
- [ ] At least one pointer in a class
#### `Shape`:
- [ ] Pure virtual functions `draw`, `move`, `perimeter`, and `area`.
- [ ] Each shape needs a unique id
- [ ] Disable copy constructors
- [ ] Child classes `Line`, `Polyline`, `Polygon`, `Rectangle`, `Ellipse`, `Text`
- [ ] Overloaded == and < operators, which compare ids to facilitate sorting.
- [ ] Shape properties (refer to `shape_input_file_specs.txt`)
#### `vector`:
- [ ] templated
- [ ] constructor for one or more arguments
- [ ] copy constructor
- [ ] copy assignment
- [ ] move constructor
- [ ] move assignment
- [ ] basic iterator member type
- [ ] `begin()` and `end()` functions
### Interface:
- [ ] clear and easy to use
- [ ] should handle invalid input
### Extra Credit:
- [ ] Implement custom `selection_sort` algorithm to sort by id
- [ ] Implement custom `compare_shape_perimeter` algorithm to sort by perimeter
- [ ] Implement custom `compare_shape_area` algorithm to sort by area
## Final Checkpoint:
- [ ] Provide customer reviews and solicit for more
- [ ] Provide contact us, create a team name and logo
- [ ] Display all graphics objects in a render area
- [ ] Read from a shape file
- [ ] Admin should be able to move shapes
- [ ] Produce a report sorted by shape id
- [ ] Produce an area report of all shapes with area
- [ ] Produce a perimeter report of all shapes with perimeter
- [ ] Save work between executions
## Submission:
- [ ] URL to this repo (add \@JKATHSADDLEBACKEDU as a contributor)
- [ ] white box testing results
- [ ] Qt project
- [ ] UML class diagrams
- [ ] text file documenting which source file and line number satisfies each requirement
- [ ] agile product backlog and all scrum documentation
- [ ] doxygen class documentation
- [ ] valgrind memory leak check
- [ ] completed team member contribution form (to be completed by each team member)
