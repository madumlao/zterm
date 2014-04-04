zterm
=====

Shortcut commands for opening gnome-terminal into a rails directory.
- can run with zeus
- can run with bundler
- can be used to create an application launcher

Usage
-----
	# rails server -p 3000 -e development
	zterm -r /my/rails/root start

	# rails server with port and environment
	zterm -r /my/rails/root -p 4000 -e production

	# open a terminal in the rails root
	zterm -r /my/rails/root cd

	# rails console
	zterm -r /my/rails/root console

	# rails dbconsole
	zterm -r /my/rails/root dbconsole

	# run a server with bundle exec
	zterm -br /my/rails/root start

	# run a console with zeus
	zterm -zr /my/rails/root console

	# run a server with bundler and zeus
	zterm -zbr /my/rails/root console

Desktop Shortcut
----------------

There is a .desktop file that comes with zterm. Customize this for your application, make it executable, then add it to your launcher / menu / desktop. Voila! Single / Double click starts up your rails server!

If you're feeling pretty good go take your application's logo and put that in the Icon directive in the .desktop file.
