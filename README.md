# PIISeeker.yaml

 powerful script designed to probe and detect potential leaks of Personally Identifiable Information (PII).

 this script detect leaks like:

1.Usernames

2. SSN Exposure
 
3. Date of Birth Exposure
  
4. Address Exposure
 
5. Financial Information Exposure
 
6. National Identification Number Exposure
 
7. Driver's License Number Exposure

8. Passport Number Exposure
 
9. Vehicle Registration Number Exposure

### Usage

#### With list
```
./nuclei -l LIST -t PIISeeker.yaml
```
#### With URL

```
./nuclei -u URL -t PIISeeker.yaml
```

### Note : 
 For better performance and results use it with JS files  
> The PIISeeker Template is intended for legitimate security testing and vulnerability assessment purposes only.
