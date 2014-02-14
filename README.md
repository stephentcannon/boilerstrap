# boilerstrap

a minimalistic meteor bootstrap boiler plate

# dependencies
npm install -g meteorite
 or
sudo -H npm install -g meteorite

mrt remove autopublish

mrt remove remove insecure

mrt add accounts-ui

mrt add accounts-password

mrt add accounts-ui

mrt add accounts-password

mrt add spin

mrt add iron-router

mrt add bootstrap-3

mrt add font-awesome

# directory structure

|-client
|	|
|	--lib - javascript libaries not part of templates and not packaged
|	|
|	--template - template, layout and all view assets
|	|  |
|	|  --css - all css
|	|
|	--views - all views, helpers and events
|	   |
|	   --includes - all reusable included components not packaged.
|	
|-lib - shared code that needs to be loaded first
|
|-packages - packages
|
|-private - private server side assets

public - public assets

server - server side