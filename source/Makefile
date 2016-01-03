run:
	cp -R static-html/* ..
	pelican -t theme -s settings.py -o .. content
	cp ../pages/* ../
	rm -rf ../pages/
	rm -rf ../theme/

init:
	pip install -r requirements.txt
