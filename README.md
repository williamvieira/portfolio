```php
<?php
namespace WilliamVieira;

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
            'languages'  => ['HTML', 'CSS', 'JavaScript', 'PHP', 'C#'],
            'frameworks' => ['VueJs', 'React', 'Laravel', 'WordPress', 'CodeIgniter', 'Ionic'],
            'databases'  => ['MySQL', 'PostgreSQL', 'SQL Server'],
            'versioning' => ['GitHub']
        ];
    }
}
```

---

You can reach me via [Linkedin] (https://www.linkedin.com/in/williamvieira-tech/) [Portfolio] (https://williamvieira.tech/)
