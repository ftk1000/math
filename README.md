# math

* [https://github.com/rossant/awesome-math#foundations-of-mathematics](https://github.com/rossant/awesome-math#foundations-of-mathematics)<br>

* [https://www.desmos.com/calculator](https://www.desmos.com/calculator/dxkknajdqb)

* [https://www.wolframalpha.com/](https://www.wolframalpha.com/)

* [simulated-annealing-from-scratch-in-python](https://machinelearningmastery.com/simulated-annealing-from-scratch-in-python/)

* [no-free-lunch-theorem-for-machine-learning](https://machinelearningmastery.com/no-free-lunch-theorem-for-machine-learning/)

* []()


* []()
 
## [https://www.face-rec.org/algorithms/](https://www.face-rec.org/algorithms/)



### [Erdos Number Project](https://oakland.edu/enp/)
* [EN-1 list](https://oakland.edu/enp/thedata/erdos1/)
* [EN-2 list](https://oakland.edu/enp/thedata/erdos2/)
* [EN-1 list on a new webpage](https://sites.google.com/a/oakland.edu/jerry-grossman-home-page/home/the-erdoes-number-project/the-erdoes-number-project-data-files/erdos1)
* []()
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

