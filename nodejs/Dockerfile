FROM joergw78/devcontainer:0.1

RUN pacman -S nodejs npm --noconfirm
RUN npm install -g nodemon

# www (default)
EXPOSE 80

# nodejs remote debugging
EXPOSE 9229

# liveserver (auto reloads browser)
EXPOSE 5500
