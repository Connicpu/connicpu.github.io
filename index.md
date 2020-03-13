# Resume

Download a copy of my resume [here](resources/Resume_ConnieHilarides.pdf)

# Contact

- Email: [connie@connieh.com](mailto:connie@connieh.com)
- [GitHub](https://github.com/connicpu)
- [LinkedIn](https://www.linkedin.com/in/connicpu/)

# Projects

## Academic Projects

### HoloTowers

<iframe width="560" height="315" src="https://www.youtube.com/embed/rqgNteujCW8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

This game was built as part of a multi-semester team project at DigiPen,
from Sep 2016 - April 2017.
We were very excited for the opportunity to work with the Microsoft HoloLens,
so we set out to build a game that we thought would be enhanced by being
able to effect the gameplay through the placement of real world objects.
We settled on tower defense with the idea that you could slow enemies down
by placing your base at a high point in the room.

We built the game in Unity, which was a fantastic learning experience.
I spent a significant portion of the project learning the Unity/HoloLens
integration APIs so that we could do world mapping for the gameplay
surface, as well as the user interaction with the click gesture.
I also wrote the pathfinding for the enemies on the tower defense field.

### Pirate Hunt

<img alt="Pirate Hunt Gameplay Screenshot" src="images/pirate_gameplay1.png" style="width: 70%; max-width 800px;"/>

This game was built as part of a multi-semester team project at DigiPen,
from Sep 2015 - April 2016.
We wrote the game engine in C++, with most of the higher level logic
and UI code written in a dialect of Lua.
I lead the team on the technical direction of the project and
created the framework for most of the game's rendering system,
as well as integrating PhysX for the physics engine, using luabind
for integrating lua and allowing scripts to interact with the engine,
built the framework for the AI,
and created the UI system and level editor.

[Download the game here](resources/Pirate_Setup.exe)

### Roguebot

2D turn-based rogue-like dungeon crawler

<img alt="Roguebot Gameplay Screenshot" src="images/roguebot_gameplay1.jpg" style="width: 70%; max-width 800px;"/>

This game was built as part of a multi-semester team project at DigiPen,
from Sep 2014 - April 2015.
The game was written primarily in C++, with Ruby scripting.
I lead the team's technical direction, and primarily built the game's
core engine, rendering, and scripting integration.

[Download the game here](resources/Roguebot_Setup.exe)

## Open Source work

### directx-rs

Rust bindings for various DirectX APIs, currently with a focus on Direct2D.
This set of libraries is still very much a work in progress.

- [`direct2d` docs](https://docs.rs/direct2d/0.2.0/direct2d/)
- [`math2d` docs](https://docs.rs/math2d/0.1.3/math2d/)
- [Repository](https://github.com/connicpu/directx-rs)

### com-impl

A Rust library for generating implementations of COM interfaces.
Referenced in [this MSRC article](https://msrc-blog.microsoft.com/2019/10/08/designing-a-com-library-for-rust/).

- [Documentation](https://docs.rs/com-impl/0.1.1/com_impl/)
- [Repository](https://github.com/Connicpu/com-impl)

### Other contributions

#### [winapi](https://github.com/retep998/winapi-rs)

I've contributed a lot of Windows API bindings to the `winapi` Rust library,
including a [large chunk](https://github.com/retep998/winapi-rs/pull/164)
of the Direct2D, DirectWrite, and DXGI bindings.

