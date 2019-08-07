FROM qssssys/webap:alpine3.10-httpd2.4-php7.3

ADD ./application.conf /etc/apache2/virtualhost.d/application.conf
RUN dos2unix /etc/apache2/virtualhost.d/application.conf

RUN npm install -g mklicense
RUN sudo -u appadm touch ~appadm/.npmrc

