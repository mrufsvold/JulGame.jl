![julGame-Logo-2023](https://github.com/Kyjor/julGame.jl/assets/13784123/6a3b2ef3-1c8d-4e21-bc0a-9a7b4bbed0a5)

julGame is an open-source game engine meant for creating 2D games using the Julia programming language. https://julialang.org/
# Why are you making this?
Because I find Julia interesting and I've always wanted to create a game engine. I would like to see a game dev scene around it as there isn't much of one now. I am not a Julia programmer (nor an experienced game engine creator), so I am sure there is a lot I am doing wrong. If you see anything that I can fix, please just let me know with a discussion or an issue.

# How to install as a package: 
`] add https://github.com/Kyjor/julGame.jl for main`

`] add https://github.com/Kyjor/julGame.jl#develop for develop`

# How to build the platformer project

Navigate to demos, and start the julia repl in this folder. Use cd("full\\path\\to\\demos"). Run "using PackageCompiler" (install PackageCompiler if you haven't already). Run the function create_app("platformer","NameOfTheBuildFileFolder"). Replace "NameOfTheBuildFileFolder" with whatever you want to name it.
