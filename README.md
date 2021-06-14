## Hi 👋, I'm Searge

### An artist passionate with code from Ukraine

<img src="https://komarev.com/ghpvc/?username=searge&label=Profile%20views&color=0e75b6&style=flat" alt="searge" />

- 🌱 I’m currently learning **Full Stack Web Development**

```python
"""Creating class for keeping track of knowledge."""
import json
from pprint import pprint
from dataclasses import asdict, make_dataclass

person = make_dataclass('Person',
                        [('nick', str),
                         ('name', str),
                            ('languages', list[str]),
                            ('databases', list[str]),
                            ('misc', list[str]),
                            ('ongoing', list[str])],
                        namespace={
                            'to_json': lambda self: json.dumps(
                                asdict(self), indent=4)})
# %%

if __name__ == '__main__':
    languages = ['Python', 'JS', 'HTML', 'CSS', 'XPath', 'Lisp']
    databases = ['SQLite', 'PostgreSQL', 'DynamoDB', 'Redis']
    misc = ['Linux', 'Shell', 'Docker', 'AWS']
    ongoing = ['Full Stack Web', 'Laravel', 'AWS']

    me = person('@Searge', 'Sergij Boremchuk',
                languages, databases, misc, ongoing)

    pprint(me.to_json())

# %%

```


<a href="https://www.linux.org/" target="_blank">
  <img
    src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg"
    alt="linux"
    width="32"
    height="32"
  />
</a>
<a href="https://git-scm.com/" target="_blank">
  <img
    src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg"
    alt="git"
    width="32"
    height="32"
  />
</a>
<a href="https://www.gnu.org/software/bash/" target="_blank">
  <img
    src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg"
    alt="bash"
    width="32"
    height="32"
  />
</a>
<a href="https://aws.amazon.com" target="_blank">
  <img
    src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg"
    alt="aws"
    width="32"
    height="32"
  />
</a>
<a href="https://www.docker.com/" target="_blank">
  <img
    src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg"
    alt="docker"
    width="32"
    height="32"
  />
</a>
<a href="https://www.python.org" target="_blank">
  <img
    src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg"
    alt="python"
    width="32"
    height="32"
  />
</a>
<a href="https://www.haskell.org/" target="_blank">
  <img
    src="https://upload.wikimedia.org/wikipedia/commons/1/1c/Haskell-Logo.svg"
    alt="haskell"
    width="32"
    height="32"
  />
</a>
<a href="https://www.postgresql.org" target="_blank">
  <img
    src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg"
    alt="postgresql"
    width="32"
    height="32"
  />
</a>
<a href="https://redis.io" target="_blank">
  <img
    src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg"
    alt="redis"
    width="32"
    height="32"
  />
</a>
<a href="https://www.tensorflow.org" target="_blank">
  <img
    src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg"
    alt="tensorflow"
    width="32"
    height="32"
  />
</a>

### My Stats

[![Searge`s github stats](https://github-readme-stats.vercel.app/api?username=searge&show_icons=true&)](https://github.com/anuraghazra/github-readme-stats)

[![Searge's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=@Searge&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=searge&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
