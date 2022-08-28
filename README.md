# Unknownapps.xyz

Unknownapps.xyz likes to hide their files, and don't do it in a very good and efficient way.
They install the main loader using a placeholder loader that writes the binary image to your disk.
Once it's downloaded, they make their file a superhiddenfile & rename it. They mostly download to SystemDrive\Windows\Fonts & change the extention to a bat file.
They have very many checks, but don't make their placeholder as useful as it could be, they don't have any secondary integrity checks. It's all in the main product.
If you were to remove the superhiddenfile attribute; and copy the file, you can't. Simply because of the permissions being Read only once ran.
What you can do, is you can change the security page to read+write for all users, so you can modify it.
Once that's done with, the main module uses an older version of vmp. You can dump the main-module using VMPDump, KsDumper (and) or others.

The code isn't really clean as i'm sure it uses external resources for internal packing, I was only really trying to get hold of the main file, so enjoy!
