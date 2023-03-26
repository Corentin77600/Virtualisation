FROM nginx:latest
COPY index.html /usr/share/nginx/html/index.html
COPY --from=service-image /usr/share/nginx/html/diag_circ.html /usr/share/nginx/html/
COPY --from=service-image /usr/share/nginx/html/diag_ope.html /usr/share/nginx/html/
COPY --from=service-image /usr/share/nginx/html/histo.html /usr/share/nginx/html/
COPY --from=service-image /usr/share/nginx/html/map.html /usr/share/nginx/html/
EXPOSE 80