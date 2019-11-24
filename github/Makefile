git: 
	rst2html5.py git.rst >git.html && firefox git.html	

bash:	
	rst2html5.py bash.rst >bash.html && firefox bash.html	

deploy:
	. ~/projs/website-dev/bin/activate && \
	cd ~/projs/website-dev/website && make build && make deploy

kernel:
	rst2html5.py linux/kernel-devel.rst > kernel-devel.html && firefox kernel-devel.html	
	
github:
	rst2html5.py github-tut.rst > github-tut.html && firefox github-tut.html
lkm:
	rst2html5.py linux/lkm.rst > lkm.html && firefox lkm.html	

dict: 
	rst2html5.py dict/dict
qt:
	rst2html5.py qt.rst >qt.html && firefox qt.html	
qtips:
	rst2html5.py qtips.rst >qtips.html && firefox qtips.html	
cpp:
	rst2html5.py cpp.rst >cpp.html && firefox cpp.html	
vim:
	rst2html5.py vim.rst >vim.html && firefox vim.html	
cmake:	
	rst2html5.py cmake.rst >cmake.html && xdg-open cmake.html	
2k:	
	rst2html5.py 2k.rst >2k.html && xdg-open 2k.html	
rst:	
	rst2html5.py rst.rst >rst.html && firefox rst.html	
web:
	rst2html5.py web.rst >web.html && firefox web.html	
nikola:
	rst2html5.py nikola.rst >nikola.html && firefox nikola.html	
commit: clean 
	git add *
	git commit -am "auto update"
push: 
	git push origin master
clean:
	rm -rf *.html

