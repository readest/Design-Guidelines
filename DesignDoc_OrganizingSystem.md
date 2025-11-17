Addressing issue #1577
# Overview
The goal is to develop an interface for categorizing books the library view. The two core systems for organizing books are Groups and Collections. A book can belong to multiple Collections, but only one Group per book.

When designing we should also consider three types of devices: phone, tablet, and desktop (these three are used often and are different enough to be in their own categories). For the this phase of development, I will focus on developing for the tablet. Many tablet developments would also improve the desktop. 

As of now, this is what the Library view looks like:

<img width="799" height="585" alt="image" src="https://github.com/user-attachments/assets/a5abf222-a327-452c-acbd-dd5947335f3f" />

# Benchmarking
Here is the FigJam I use to store research, you can find the Benchmark board in thie [FigJam page](https://www.figma.com/board/Z1EGVXwxTG67sIXCL3FXCV/Readest?node-id=22-127). Overall, Apple Books should be benchmarked for UI maturity, but for usability, let's look at **ReadEra**.
- Each book unit has a visible toolbar that includes Metadata Editor and Star feature, while you need to long press the cover in Readest to see the Metadata. A few participants completely missed this during my first round of user testing.
- They display Title and Bookcover seperately, which is particularly helpful since not all documents imported by users have a cover nor they need one.

# User Research (Round One) - Key Takeaways
Interviewed 4 Participants on their e-reader uses, I also scored Reddit for some extra infos but it's scarce on there. Please feel free to share your personal experience if you happen to read on your tablet.
- Touchscreen device users tend to organize their libraries less than Desktop users.
  - Some of them organize on Desktop and read on Tablet/Phone.
  - A majority of them don't have subfolders because they prefer to know everything that is in that folder at first glance.
- Touchscreen device users (especially the ones on Phones) usually rely on the Recently Read or the Search section to access their Books instead of the Library view.
- No mention of tags <-- I'm hypothesizing this should be majorly designed for Desktop people (and Tablet people at one point).

# Points that could be addressed in seperate Issues
- Some features need to be more visible and not hidden in another button (Grid to List, Metadata editor)
- The default cover template looks confusing for participants (they prefer the Apple Books default covers because they have different colors for each book; one participant said the same grey covers could get very confusing if they have a hundred books without covers)
- Formating features need to be communicated more efficiently (what is Padding? an average user wouldn't know that. Benchmark Apple Books and Figma for this). Also, remove this feature from Library view, only display it in Reader view.


# Possible Exploration
- A color-coding system using Groups so they seperate Collections and Books rows on the Navbar (to be prototyped)
- Could the cross-device sync of Readest be utilized? (Desktop flow is more organizational and Touchscreen flow is for reading)
- Concepting a hotkey menu for each Book unit on the Library view to make sure Organizing is possible and smooth on all devices

# Information Architecture

<img width="702" height="493" alt="image" src="https://github.com/user-attachments/assets/95af6a97-c505-42f5-91a1-f29a2414ce53" />

I would argue that we don't need a naming system for Groups (users can just use sub-collections if they need to), Groups can be used as a color-coding system to cluster Collection together on Sidebar.

# To-dos (updating)

- [x] User research (look at people who uses E-readers regularly)
  - [ ] Use cases
- [x] Information architecture of Library view
- [ ] Lo-fi mockups (very important to prototype the nav sidebar and how Groups and Collections function)
- [ ] MVP Library view
