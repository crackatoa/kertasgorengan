## Subdomain

```
amass enum -passive -d domain.com -o output.amass
```
```
cat list_domain.txt | ./bin/massdns -r lists/resolvers.txt -t A -o S -w result.txt
```

## Web Screenshot

```
webscreenshot -i list_domain.txt -o output_dir
```
