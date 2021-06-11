FROM fastai/jekyll:2020-12-30

RUN pip install git+https://github.com/yacchin1205/nbdev.git@fix/attached-images

WORKDIR /fastpages
COPY . .
RUN chmod u+x action_entrypoint.sh
RUN chmod u+x word2post.sh
RUN dos2unix /fastpages/*.sh

CMD [ "/fastpages/action_entrypoint.sh" ]
