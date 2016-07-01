# A Discipline for Software Engineering

The book describes what is a "Personal software process" (PSP), why it is needed and where it fits (or not). It provides the framework for statistically managed software engineering discipline and shows how PSP can be used in work.

## Chapter 1: The Personal Software Process Strategy
Introduction to the core concept of PSP: measurable principles for managing individual's software engineering contributions.

### Logic
- Purpose:helps individual software engineer plan better, track performance precisely, and measure quality of work.
- Motivation: lack of software development principles
   - Software systems are large and complex
   - Like an orchestra, although it consists of many instruments, any sour note will standout
   - Similarly, bad individual contribution can be detrimental to the overall product
   - Industry relies on rigorous testing -- doesn't always work

### What is software process

Sequence of steps required to develop and maintain software.

Its benefit include:
- Effective communications
- Enhance everyone's understanding, process automation and personnel mobility
- Project reuse
- Process evolution
- Aid process management

Therefore several levels of process maturity can be defined:

1. Initial Stage. Ad hoc and chaotic.
2. Repeatable.
   - Software configuration management.
   - Software quality assurance.
   - Software subcontract management.
   - Software project tasks defined.
   - Project planning and requirements.
3. Defined.
   - Peer reviews.
   - Intergroup coordinations.
   - Software product engineering.
   - Integrated software management.
   - Training.
   - Software process definition.
4. Managed.
   - Quality management.
   - Quantitative process management.
5. Optimizing.
   - Process changes.
   - Technology changes.
   - Defect preventions.


### Personal responsibilities
Know your capabilities (more importantly, personal strengths) and improve.

PSP is a process that can help you improve and very rewarding in the long run. It doesn't suit every one though. Being totally objective about one's performance and have the persistence and dedication to stick with it is required.

### PSP Strategy
1. Start to have time recording and defect recording process. Make standard for defect types.
==> 1.1 Establish coding standard, code size measurement, and process improvement proposal.
2. Code size estimating and test report.
==> 2.1 Test planning and schedule planning.
3. Code reviews + design reviews
==> 3.1 Design templates.
4. Cyclic development.

### Productivity
- Productivity is directly proportional to complexity of the project
- Additional commenting and documentation will make productivity appear to decline
- Test time will be proportional to the amount of variations in number of defects
- Code quality concerned, not the simpler the better
- Variation is large between different individuals and appear to be a long tail. Best:worst > 20:1
- PSP practice will converge the variations of develop times, and usually will enhance productivity

## Chapter 2. The Baseline Personal Process
### Baseline process and elements

1. Planning
2. Development
   - Design
   - Code
   - Compile
   - Test
3. Postmotem

Results: finished product, project and process data, summary report.

Process:
* Phase 1: Planning
   * Program requirements
      * Produce requirement statement for the program
      * Ensure the requirements statement is clear and unambigous
      * Resolve questions
   * Estimate Resources
      * Make best estimate of the time required to develop this program
* Phase 2: Development
   * Design
      * Review the requirements and produce a design to meet them
      * Record time
   * Code
      * Implement the design
      * Log the design defects
      * Record time
   * Compile
      * Compile the program until bug free
      * Log defects
      * Record time
   * Test
      * Test until all tests run bug free
      * Log defects
      * Record time
* Phase 3: Postmortem
   * Defects
      * Which phase injected/removed
      * Type
      * Fix time
   * Time spent in each phase
