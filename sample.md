{% terminal %}
$ echo "Hello world!"
Hello world!
$ date
Sat Nov 11 09:56:26 CET 2023
$ cat <<END
/This will disappear in void
/END
$ echo 'this line is an artificially long comand' | sed 's/comand/command to test rendering/' | grep line | tee /dev/null
this is an artificially long command to test rendering
$ echo
{% endterminal %}
