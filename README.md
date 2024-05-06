```php
<?php
namespace WlliamVieira;

class About extends Me
{
    public function getPersonalInfo(): array
    {
        return [
            'name'     => 'William Vieira',
            'position' => 'Full Stack Developer',
            'location' => 'São Paulo, Brazil 🇧🇷',
            'website'  => 'https://williamvieira.tech/'
        ];
    }
    public function getSkills(): array
    {
        return [
            'languages'  => ['JavaScript', 'PHP'],
            'frameworks' => ['React', 'React Native', 'Laravel', 'WordPress'],
            'databases'  => ['MySQL', 'PostgreSQL', 'SQL Server']
        ];
    }
}
```

---

You can reach me via [Linkedin] (https://www.linkedin.com/in/williamvieira-tech/)
