# LFI
python local and remote file inclusion scanner for testing web servers 
# Running
---------------------------------------------
python lfi.py -u http://www.somesite.com?page=
python lfi.py -d 

# Usage 
---------------------------------------------
Usage: lfi.py [options]

Options:
  -h, --help            show this help message and exit
  -u http://www.example.com/index.php?page=, --url=http://www.somesite.com/index.php?page=
                        URL of target
  -c, --crawl           Crawl website enabled
  -d, --dork            provide a google dork
