update pacman

run  for x in $(cat package_list.txt); do pacman -S $x; done

or if that doesnt work try

pacman -S `cat package_list.txt`
-This will also work, but Pacman will exit if you have a package
-installed that is not in the repositories.

then use yadm to put dotfiles where they go
set background and run 'wal -i path/to/img.jpeg'

most things should be set up at this point