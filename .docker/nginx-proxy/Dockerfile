FROM jwilder/nginx-proxy

RUN mkdir -p /etc/nginx/vhost.d && \
    echo "keepalive_timeout  600;" > /etc/nginx/vhost.d/default && \
    echo "fastcgi_read_timeout 600;" >> /etc/nginx/vhost.d/default && \
    echo "types_hash_max_size 2048;" >> /etc/nginx/vhost.d/default && \
    echo "proxy_connect_timeout 600;" >> /etc/nginx/vhost.d/default && \
    echo "proxy_send_timeout 600;" >> /etc/nginx/vhost.d/default && \
    echo "proxy_read_timeout 600;" >> /etc/nginx/vhost.d/default && \
    echo "send_timeout 600;" >> /etc/nginx/vhost.d/default

