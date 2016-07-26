# read-from-complex-plist

This is a sample demonstration about how to read test summary from

   - TestSummary.plist file

When you run an Xcode UI Test, it will generate a TestSummary.plist file in 
  -/Users/username/Library/Developer/Xcode/DerivedData/projectname/Logs/Test/
  
This TestSummary.plist file is more complex.

First, copy your TestSummary.plist file to Documents directory.
Than use my functions to get the category wise test summary.

Test summary will be stored in TestSummary.txt file in documents directory.
