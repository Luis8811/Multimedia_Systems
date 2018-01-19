# slides

Slides of the subject "Sistemas Multimedia"

## Clone with:
```
git clone --recurse-submodules git@github.com:Sistemas-Multimedia/Multimedia_Systems.git
```

## Update with:
```
git pull
git submodule update --remote 
```

## Push
```
# In the modified submodule and in all the parent directories
git commit -m "..."; git push
```

## Show slides with:
```
# Reveal (default)
jupyter nbconvert Multimedia_Systems.ipynb --to slides --post serve

# Reveal with vertical scrolling
jupyter nbconvert Multimedia_Systems.ipynb --to slides --post serve --SlidesExporter.reveal_scroll=True

# Reveal selecting theme
jupyter nbconvert Multimedia_Systems.ipynb --to slides --post serve --SlidesExporter.reveal_theme=simple

# Reveal selecting port
jupyter nbconvert Multimedia_Systems.ipynb --to slides --post serve --ServePostProcessor.port=8010

# Full (single page)
jupyter nbconvert Multimedia_Systems.ipynb --to slides --template full.tpl

## full.tpl can be located at:
~/.pyenv/versions/3.6.3/lib/python3.6/site-packages/nbconvert/templates/html/full.tpl
```

