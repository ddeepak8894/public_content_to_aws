#Run Stage Start
FROM nginx
COPY default.conf /etc/nginx/conf.d/default.conf
#Copy production build files from builder phase to nginx
COPY build /usr/share/nginx/html
