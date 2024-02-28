## about_me.rb

```ruby
class RubyDeveloper < Developer
end

luckvc = RubyDeveloper.new

luckvc.name = 'Lucas Vasques'
luckvc.field = 'Back-end Development'
luckvc.languages = ['Portuguese', 'English']
luckvc.location = 'Brazil'
luckvc.email = 'lucasvc1996@gmail.com'

luckvc.save!

luckvc.programing_languages.create([{name: 'Ruby', description: 'Programing Language'},
                                    {name: 'Java', description: 'Programing Language'},
                                    {name: 'C', description: 'Programing Language'},
                                    {name: 'HTML', description: 'Markup Language'},
                                    {name: 'CSS', description: 'Styling Language'},
                                    {name: 'SQL', description: 'Structured Query Language'}])

luckvc.frameworks.create([{name: 'Rails', description: 'Ruby Framework'},
                          {name: 'Springboot', description: 'Java Framework'},
                          {name: 'Bootstrap', description: 'CSS Framework'}])
                          
luckvc.databases.create([{name: 'SQLite', description: 'SQL Database'},
                      {name: 'MongoDB', description: 'NoSQL Database'}])

render :contact

```
<a href="https://www.linkedin.com/in/lucas-vasques-campos/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>


