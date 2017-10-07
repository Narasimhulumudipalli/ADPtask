
FROM centos 
MAINTAINER narasimhulu
RUN yum update &&yum install -y nginx &&
yum clear &&
rm-rf/var/log/yum/lists/*
ENV nginx_run_user_www-data
ENV nginx_run_ground www-data
ENV mginx _log_dir/var//log/nginx
cmd ["/user/sbin/nginx: "-d"]
POSE 80
COPY
 docker log 
 myhtml pages.py

def wrapStringInHTMLMac( myfirstpag, 127.0.0.1/1, myfisthtml page
                         mysecongpage, 127.0.0.1/2, mysecond page
                         mythirdpage, 127.0.0.1/3, mythird page):
    import datetime
    from webbrowser import open_new_tab

    now = datetime.datetime.today().strftime("%Y%m%d-%H%M%S")
    filename = program + '.html'
    f = open(filename,'w')

    wrapper = """<html>
    <head>
    <title>%s output - %s</title>
    </head>
    <body><p>URL: <a href=\"%s\">%s</a></p><p>%s</p></body>
    </html>"""

    whole = wrapper % (program, now, url, url, body)
    f.write(whole)
    f.close()
:wq
docker build -t nginximg -f ./dockerfile nginx
docker run -d-p 80:80 -v/var/www/html:/var/www/html ngnix
