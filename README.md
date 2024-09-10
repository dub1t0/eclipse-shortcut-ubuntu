# eclipse-shortcut-ubuntu
Create an App Shortcut for Eclipse on Ubuntu


https://www.eclipse.org/downloads/packages/release/2018-12/r/eclipse-ide-java-developers


nano ~/.local/share/applications/eclipse.desktop


[Desktop Entry]
Type=Application
Name=Eclipse
Comment=Eclipse Integrated Development Environment
Icon=/opt/eclipse/icon.xpm
Exec=/opt/eclipse/eclipse
Terminal=false
Categories=Development
StartupWMClass=Eclipse


chmod +x ~/.local/share/applications/eclipse.desktop

