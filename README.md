# joe-kk-wedding
Joe and KK wedding site

aws s3 sync --acl public-read --sse --delete ~/Code/joe-kk-wedding/ s3://kk-joe --exclude 'pdf/*' --exclude 'README.md'
aws s3 sync --acl public-read --sse --delete ~/Code/joe-kk-wedding/ s3://sturgeonmoon2018.com --exclude 'pdf/*' --exclude 'README.md'
