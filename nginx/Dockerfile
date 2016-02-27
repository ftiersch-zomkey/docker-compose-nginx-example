FROM nginx

MAINTAINER Frank Tiersch <mail@ftiersch.de>

ADD workoutlottery.conf /etc/nginx/sites-available/workoutlottery.conf

RUN ln -s /etc/nginx/sites-available/workoutlottery.conf /etc/nginx/sites-enabled/workoutlottery.conf
RUN rm /etc/nginx/sites-enabled/default

CMD ["nginx"]

EXPOSE 80
EXPOSE 443
