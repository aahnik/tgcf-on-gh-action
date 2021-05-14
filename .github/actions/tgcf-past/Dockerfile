FROM aahnik/tgcf

RUN python -m venv .venv && . .venv/bin/activate && pip install --use-feature=in-tree-build /app

CMD . .venv/bin/activate && tgcf
