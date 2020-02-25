# linuxSeekText
Recursively seek text in directory folders and subfolders

### Format:

seek <searchRegexp> [--only=filterRegexp] [--exlude=filterRegexp]

  - searchRegexp: regular expression for searched text;
  - --only: include only files with regular expression filter;
  - --exclude: exlude all files with regular expression filter;

### Using examples:

seek '\bStopFactorValues\b' --only=\.[jt]s$

- will find all the files with substring 'StopFactorValues' in all *.js or *.ts files;