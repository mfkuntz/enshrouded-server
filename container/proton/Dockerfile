FROM sknnr/enshrouded-dedicated-server:proton-latest

COPY entrypoint.sh /home/steam/entrypoint.sh
COPY enshrouded_server_example.json /home/steam/enshrouded_server_example.json

RUN cat /home/steam/entrypoint.sh

WORKDIR /home/steam

CMD ["/home/steam/entrypoint.sh"]
