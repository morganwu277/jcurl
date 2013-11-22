jcurl
=====

Java implementation of a cURL (Client URL Request Library) software

usage:

    java -jar jcurl.jar

     -h,--help                       Usage help.
     -i,--include                    Include the HTTP-header in the output. The
                                     HTTP-header includes things like
                                     server-name, date of the document,
                                     HTTP-version and more...
     -inputFile <arg>                Specify file which contain a list of URL
                                     (one line per URL)
     -inputPattern <arg>             Specify regexp pattern to transform input
                                     data (see param 'inputFile' and
                                     'inputTransform') into URL
     -inputTransform <arg>           Specify substitution string to transform
                                     input data (see param 'inputFile' and
                                     'inputPattern') into URL. Use $1, $2, ...
                                     for catched group.
     -manual                         Specifies a custom request method to use
                                     when communicating with the HTTP server.
                                     The specified request will be used instead
                                     of the method otherwise used (which
                                     defaults to GET). Read the HTTP 1.1
                                     specification for details and explanations.
                                     Common additional HTTP requests include PUT
                                     and DELETE.
     -V,--version                    Displays information about jcURL version it
                                     uses.
     -X,--request <command>          Specifies a custom request method to use
                                     when communicating with the HTTP server.
                                     The specified request will be used instead
                                     of the method otherwise used (which
                                     defaults to GET). Read the HTTP 1.1
                                     specification for details and explanations.
                                     Common additional HTTP requests include PUT
                                     and DELETE.
