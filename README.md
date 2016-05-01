## Implementation of B-multicast and R-multicast using Julia.

<nav style='font-align:justify'>The main goal of the project is to implement, using the programming language Julia [1], the algorithms for B-multicast [2] and R-multicast [3] in two ways for each one - asynchronous [4] and synchronous [5]. Along with the implementation of the functions, there are counters to prospect the medium time of execution of each algorithm, with the goal to compare it and charts showing the difference between time execution of the algorithms.

This project was made to be graded at the course of <a href="https://sites.google.com/a/ic.ufal.br/andrelage/home/lectures/2015-2" target="_blank">Distributed Systems</a>, lectured by <a href="https://github.com/proflage/" target="_blank">Professor Andre Lage</a> in the <a href="http://www.ic.ufal.br" target="_blank">Institute of Computing</a> at <a href="http://www.ufal.edu.br" target="_blank">UFAL - Federal University of Alagoas</a>. You can find the template used to this project clicking <a href="https://github.com/proflage/teaching/tree/master/2015.2-SD-trabalho-pratico" target="_blank">here</a>.

In the source files, you can find:

- `Multicasts-Julia.ipnyb` to load at your Julia enviroment
- Source images used for the graphs generated

Feel free to perform a pull request to the project, implementing additional functions or improving some of the existents.<br>
This baby project was made using <a href="https://juliabox.org" target="_blank">JuliaBox</a>, we recommend you also use the same tool, listed below.

</nav>

### JuliaBox

<ul>
	<li>Sign in at <a href="https://juliabox.org" target="_blank">JuliaBox</a> using your google account
		<ul>
 			<li>If you do not have a google account, you can create one at <a href="https://accounts.google.com/sigNup" target="_blank">Google Accounts</a></li>
 		</ul></li>
 	<li>On the right sub-topmenu, click on the first button <b><i>Upload</i></b>
 		<ul>
 			<li>Select the file <b><i>Multicasts-Julia.ipynb</b></i> that you've downloaded along with the repository</li>
 		</ul></li>
	<li>Wait for Julia to auto-prepare the environment for you</li>
 	<li>You are good to go!</li>
 </ul>

### Local installation

If preferred, the user can use [IJulia Notebook](https://github.com/JuliaLang/IJulia.jl) in your local machine.<br>
Just install IJulia Notebook and load the file `Multicasts-Julia.ipynb`. 

### References

[1] Julia programming language, available at < http://julialang.org/ > <br>
[2] Basic multicast, available at < https://en.wikipedia.org/wiki/Multicast > <br>
[3] Reliable multicast, available at < https://en.wikipedia.org/wiki/Reliable_multicast > <br>
[4] Asynchronous communication, available at < https://en.wikipedia.org/wiki/Asynchronous_communication > <br>
[5] Synchronous communication, available at < https://en.wikipedia.org/wiki/Synchronous_serial_communication > <br>
