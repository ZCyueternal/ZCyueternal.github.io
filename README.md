## To Run locally
1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change. (PS: `./_site` will be generated)
2. if Step 1 return `Permission denied - bind(2) for 127.0.0.1:4000`, Run `netstat -aon | findstr "4000"` to find the number of conflict service and kill it. (Mostly because of Foxit Service)

## Edit
1. `./_config.yml` is the setting for entire site.
2. `_data/navigation.yml` contains various parts. Comment or uncomment the options you want.
3. `_pages/about.md` is the homepage.
4. `_pages/publications.md` contains some journal, conference and arxiv papers.
5. `_pages/cv.md` is  cv/resume page.