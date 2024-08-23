# Moe-Counter

多种风格可选的萌萌计数器

![Moe-Counter](https://moe-counter.sakuras.in/get/@Moe-counter.github)

<details>
<summary>More theme</summary>

##### asoul
![asoul](https://moe-counter.sakuras.in/get/@demo?theme=asoul)

##### moebooru
![moebooru](https://moe-counter.sakuras.in/get/@demo?theme=moebooru)

##### rule34
![Rule34](https://moe-counter.sakuras.in/get/@demo?theme=rule34)

##### gelbooru
![Gelbooru](https://moe-counter.sakuras.in/get/@demo?theme=gelbooru)</details>

## Demo
[https://count.getloli.com](https://moe-counter.sakuras.in)

## Usage

### Install

#### Deploying on your own server

```shell
$ git clone https://github.com/journey-ad/Moe-Counter.git
$ cd Moe-Counter
$ yarn install

$ yarn start
```

### Configuration

`config.yml`

```yaml
app:
  # site: https://count.getloli.com # your website
  port: 3000

db:
  type: sqlite # sqlite or mongodb
```

If you use mongodb, you need to specify the environment variable `DB_URL`

```shell
# eg:
export DB_URL=mongodb+srv://account:passwd@***.***.***.mongodb.net/db_count
```



## Credits

*   [replit](https://replit.com/)
*   [A-SOUL_Official](https://space.bilibili.com/703007996)
*   [moebooru](https://github.com/moebooru/moebooru)
*   rule34.xxx NSFW
*   gelbooru.com NSFW
*   [Icons8](https://icons8.com/icons/set/star)

## License

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fjourney-ad%2FMoe-Counter.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fjourney-ad%2FMoe-Counter?ref=badge_large)
