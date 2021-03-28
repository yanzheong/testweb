# Personal Website

Route 53 DNS: https://pengalex.com

### todos:

\*\*1. Renew domain ends ~ Aug 2021: transfer to alexpeng.me w/ tls/ssl

## Environments

### Development

`jekyll serve` @ PORT 4000

### Production

Push to AWS S3 buckets

1. `bundle exec jekyll build`
2. `s3_website push`

Note: s3 console -> remove .html extensions except index.html
