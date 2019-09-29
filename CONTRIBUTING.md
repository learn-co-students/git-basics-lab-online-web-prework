this lab
  1) has a folder named my-repository
  2) has a valid git repository initialized for the my-repository folder
  3) has a README.md file in the my-repository folder
 
the local repository
  4) has README.md as a tracked file
  5) has at least one commit
  6) has been pushed up to the remote repository
 
 
0 passing (42ms)
6 failing
 
1) this lab
     has a folder named my-repository:
   AssertionError: no folder name "my-repository" was found: value: expected './my-repository' to exist
    at Function.<anonymous> (node_modules/chai-fs/lib/assertions/directory.js:21:53)
    at Function.ctx.(anonymous function) [as directory] (node_modules/chai/lib/chai/utils/addMethod.js:41:25)
    at Function.assert.isDirectory (node_modules/chai-fs/lib/assertions/directory.js:34:35)
    at Context.it (test/index-test.js:11:19)
    ...