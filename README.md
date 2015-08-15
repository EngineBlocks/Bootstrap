# Engine Blocks
The main project with several sub-repositories. The goal is to have a modular engine with flexible components which can be integrated where and when needed. Each component can be written for several platforms and languages, but the interfaces should be as generic as possible to improve portability.

# Bootstrap
The bootstrap component will set up a framework with an event loop. It should be possible to set this up from several places, like the activity creation callback for Android, or the main entry point in c++ for iOS.
