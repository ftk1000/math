# math

* [https://github.com/rossant/awesome-math#foundations-of-mathematics](https://github.com/rossant/awesome-math#foundations-of-mathematics)<br>

* [https://www.desmos.com/calculator](https://www.desmos.com/calculator/dxkknajdqb)

* [https://www.wolframalpha.com/](https://www.wolframalpha.com/)

* [simulated-annealing-from-scratch-in-python](https://machinelearningmastery.com/simulated-annealing-from-scratch-in-python/)

* [no-free-lunch-theorem-for-machine-learning](https://machinelearningmastery.com/no-free-lunch-theorem-for-machine-learning/)

* []()

# LaTeX
* [Getting started with LaTeX](https://math.vanderbilt.edu/bohmanar/latex.html)

* []()

* []()
 
## [https://www.face-rec.org/algorithms/](https://www.face-rec.org/algorithms/)

## Reading

* [High-Dimensional_Data_Analysis_The_Curses_and_Blessings_of_Dimensionality, David Donoho](https://www.researchgate.net/publication/220049061_High-Dimensional_Data_Analysis_The_Curses_and_Blessings_of_Dimensionality)
   * John Tukey was very indiosyncratic, having been home schooled, and so had unusual means of self-expression; he also drew on an unusually
broad array of knowledge (he was trained as a chemist before entering mathematics)
   * Data are here now, they’ll be coming on more and more in the future, we must analyse them, often using very humble means, and insistence on mathematics
   * Data Analysis was a potentially huge field, into which statistics – with its grounding as a subdiscipline of the mathematical sciences, via probability theory, decision theory, and analysis – fit only as a small segment.
   * data analysis is an activity all its own, a kind of lifelong avocation; one does not need to be a mathematician to be a data analyst – in fact there is no connection, one could as well be a biologist, etc.
   * a data analysis community crystallized around Tukey’s conception, and its descendant communities are visible today, a substantial body of academic and industrial statisticians that emphasize data analysis over mathematical analysis and proof.


* []()

* []()

### Erdos

* [Erdos number list at oakland.edu](https://oakland.edu/enp/thedata/erdos1/)

* []()

---------

Typical sequence after local repo files are updated:

		$ git add .

		$ git commit -m '2021.01.06'

		$ git push -u origin main
		Branch 'main' set up to track remote branch 'main' from 'origin'.



NOTE [**git push -u origin master** fails](https://stackoverflow.com/questions/60660765/error-failed-to-push-some-refs-to-https-github-com) : 

	$ git push -u origin master
	error: src refspec master does not match any
	error: failed to push some refs to 'https://github.com/ftk1000/math.git'

But this works:

	$ git push -u origin main
	Enumerating objects: 26, done.
	Counting objects: 100% (26/26), done.
	Delta compression using up to 4 threads
	Compressing objects: 100% (22/22), done.
	Writing objects: 100% (24/24), 437.74 KiB | 14.12 MiB/s, done.
	Total 24 (delta 3), reused 0 (delta 0), pack-reused 0
	remote: Resolving deltas: 100% (3/3), completed with 1 local object.
	To https://github.com/ftk1000/math.git
	   af66b23..cacbcf3  main -> main
	Branch 'main' set up to track remote branch 'main' from 'origin'.

NOTE: if some files (eg README.md) gets updated on github.com, use **git pull origin** to synch folder files with github.com files, and the do PUSH.


2021.01.05

      Quick setup — if you’ve done this kind of thing before
      or	
      https://github.com/ftk1000/math.git
      Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.

…or create a new repository on the command line

      echo "# math" >> README.md
      git init
	  touch .gitignore
      git add README.md
      git commit -m "first commit"
      git branch -M main
      git remote add origin https://github.com/ftk1000/math.git
      git push -u origin main
                
…or push an existing repository from the command line

      git remote add origin https://github.com/ftk1000/math.git
      git branch -M main
      git push -u origin main

…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

