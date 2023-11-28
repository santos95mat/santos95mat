<!---
<h1>
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?size=30&duration=3000&color=13F728&background=FF632300&center=false&vCenter=true&multiline=false&width=800&height=50&lines=Olá!+Sou+o+Matheus+%F0%9F%91%8B" alt="Typing SVG" /></a></h1>
-->

<h1>Olá! Sou o Matheus :wave:</h1>

<div> 
  <a href="https://wa.me/+5531971688746?text=..." target="_blank"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"></a>
  <a href="mailto:santos95.mat@gmail.com" target="_blank"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/msantos95/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> 
</div></br>

- :computer: Estudante de Análise e desenvolvimento de sistemas - 2⁰ Semestre.
- :video_game: Valorant low elo.
- :checkered_flag: F1 fã (o esporte)
- :rooster: Atleticano
- :beers: Filósofo de buteco (ficcionado na história da humanidade)

```Go
package main

import (
	"fmt"
)

type Person struct {
	Name     string
	Age      string
	Info     string
	Pronuns  string
	Langs    []string
	Database []string
	Tools    []string
}

func (p *Person) Greeting() string {
	greeting := fmt.Sprintf("Olá, me chamo %s, tenho %s anos e sou %s!", p.Name, p.Age, p.Info)
	return greeting
}

func main() {
	matheus := &Person{
		Name:     "Matheus Rodrigues Santos",
		Age:      "28",
		Info:     "Backend developer",
		Pronuns:  "he/him",
		Langs:    []string{"GO", "C#", "JS", "TS", "Python"},
		Database: []string{"Postgres", "MongoDB", "MySQL"},
		Tools:    []string{"Git", "Docker", "Heroku"},
	}

	fmt.Println(matheus.Greeting())
	// Olá, me chamo Matheus Rodrigues Santos, tenho 28 anos e sou Backend developer!
}
```
