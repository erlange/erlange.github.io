Created using:

	npm install -g hexo-cli
	md erlange.github.io
	cd erlange.github.io
	hexo init

Then edit _config.yml for the personal info

Then run:
	npm install hexo-deployer-git --save

Then edit _config.yml for the deployment matters

Then run:
	hexo generate --watch

Create new post:
	hexo new first-post

Create new page:
	hexo new page first-page

Pages and posts reside in erlange.github.io\source folder

Serve in localhost:
	hexo server