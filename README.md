# java-sublime-build
run sublime text JAVA code on command prompt (cmd) using build system i suggest

{ 
"cmd": 
[
	"javac", "$file_name", "&&", "start", "cmd", "/k", "java" ,"$file_base_name"
], 
"selector": "source.java",
"working_dir": "${file_path}", 

 "file_regex": "^\\s*File \"(...*?)\", line ([0-9]*)", "path" : 
"C:\\Program Files\\Java\\jdk-17.0.2\\bin",
 "shell":true
 } 
 
 
  - - - - - - - - - - - - - - - - - - - - - - - - - -
  extension: ( .sublime-build)
