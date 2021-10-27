FROM python:3.9 
COPY / ./App/ 
WORKDIR App 
RUN /bin/sh -c 'pip install --no-cache-dir --index-url https://nexus.dev.afsmtddso.com/repository/AAdepegba-Nexus-repo/simple -r requirements.txt' 
ENTRYPOINT ["python"] 
CMD ["server.py"]
