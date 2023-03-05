# Linux-Commands
1. Create a file               ->  touch <filename.txt>
2. List files & Directories    ->  ls ,ls -l,ls -A,ls -A -l
3. Copy Files                  ->  cp file.txt new-file.txt
4. Rename Files                ->  mv file.txt FILE.txt
5. Create Directories          ->  mkdir demo
6. Copy Directories            ->  cp -r dir1 dir2 
7. Moving files                -> mv file dir
8. Remove directory             ->rm -rf demo 
9. List content                 ->cat file
10. View lines                   ->head file
                                   head -n 3 file
                                   tail file
                                   tail -n 3 file
11. Search for word               -> grep word file-name
12. Filter with column            ->awk -F , '{print $1}' file.csv 
13. Find files                    ->find / -name "passwd"
14. Browse and Download           ->curl -L google.com
                                     curl -o file.zip http://domain.com/file.zip
                                    curl -O http://domain.com/file.zip 
15. 