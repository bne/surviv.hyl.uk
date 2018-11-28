# surviv.hyl.uk

## dev
`docker-compose up`

## deploy
`docker-compose run --rm site jekyll build && aws s3 sync _site s3://surviv.hyl.uk --delete --profile hyl`
