# GO-Docs
Learning Go by GOing through the Docs :P
---
Each Tutorial is separated into it's own "Subproject". I will summarize here what was learned in each tutorial for my own reference. 
---
Create a Go module
- Create and understand the use of go modules for writing modular Go
- Working with multiple modules and call from one module to another
- Error handling and Go's errors and log library
- Worked with math/rand library to generate random values, in this case, random positions in an slice
- Learned how to work with slices and maps 
- Utilized Go's built in unit testing library
- Learned how to create multiple interconnected modules, Go run for testing and Go build for generating binary executables and Go install for installing as applications

How to install the code and run it on your own machine:
- After cloning the repo navigate to the /hello directory 
- run the $ go build command to generate the necessary binary executables
- If you don't already know where the go/bin directory is on your machine run $ go list -f '{{.Target}}'
- On linux run $ export PATH=$PATH:/path/generated/using/above/command to add the Go install directory to your machines shell path
- $ go install

---

