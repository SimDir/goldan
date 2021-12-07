# golan3d
GoLang "Hello world"
Оказалось странным то что на Go нет еще 3D приложений. хотя оно и возможно.
необходимо скачать сторонние бибилотеки!
go mod init youProjName
go get github.com/go-gl/glfw/v3.3/glfw@master
go get github.com/go-gl/gl/v4.4-core/gl@master
go get github.com/go-gl/mathgl/mgl32@master
go mod tidy

...