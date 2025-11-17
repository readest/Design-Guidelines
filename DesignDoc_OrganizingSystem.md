# Overview
The goal is to develop an interface for categorizing books the library view. The two core systems for organizing books are Groups and Collections. A book can belong to multiple Collections, but only one Group per book.

When designing we should also consider three types of devices: phone, tablet, and desktop (these three are used often and are different enough to be in their own categories). For the this phase of development, I will focus on developing for the tablet. Many tablet developments would also improve the desktop. 

As of now, this is what the Library view looks like:

<img width="799" height="585" alt="image" src="https://github.com/user-attachments/assets/a5abf222-a327-452c-acbd-dd5947335f3f" />

# Benchmarking
Here is the FigJam I use to store research, you can find the Benchmark board in thie [FigJam page](https://www.figma.com/board/Z1EGVXwxTG67sIXCL3FXCV/Readest?node-id=22-127). Overall, Apple Books should be benchmarked for UI maturity, but for usability, let's look at **ReadEra**.
- Each book unit has a visible toolbar that includes Metadata Editor and Star feature, while you need to long press the cover in Readest to see the Metadata. A few participants completely missed this during my first round of user testing.
- They display Title and Bookcover seperately, which is particularly helpful since not all documents imported by users have a cover nor they need one.

# To-dos (updating)

- [x] User research (look at people who uses E-readers regularly)
  - [ ] Use cases
- [ ] Information architecture of Library view
- [ ] MVP Library view
