# Dark Mode
xdg-desktop-portal-gtk && nwg-look //kurulan temalari secip ayarlamamizi saglayan paket

# Screensaver
swayidle, swaylock paketlerini kurduk

exec-once = swayidle -w timeout 150 'swaylock -f -c 000000' timeout 200 'hyprctl dispatch dpms off' resume 'hyprctl dispatch dpms on'
