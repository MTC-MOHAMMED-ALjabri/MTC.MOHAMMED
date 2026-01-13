# UML Validation and Consistency Checklist

## Syntax Validation
- PlantUML editor reports no syntax errors.
- Diagrams render correctly as PNG.
  
## Naming Consistency
- The actor "Student" appears in both diagrams.
- Use cases match class responsibilities.

## Associations and Multiplicity
- A Student can register for one or more Courses (1..*).
- Associations are clearly labeled.

## Traceability
- "Register Course" maps to Student.registerCourse().
- "Check Prerequisite" maps to Course.checkPrerequisite().
