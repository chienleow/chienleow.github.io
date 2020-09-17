---
layout: post
title:      "Keeping Rails Project ON THE RAILS"
date:       2020-09-16 23:26:11 -0400
permalink:  keeping_rails_project_on_the_rails
---

How do I prevent my Rails project from going off the rails? Sit tight, we are going on a ride! I couldn't emphasize enough on the importance of planning, **DO NOT SKIP the [Rails Project Planning Resources](http://https://learn.co/tracks/full-stack-web-development-v8/module-13-rails/section-12-authentication/rails-project-planning-resources)!**

#### **STEP 1: Making a User Story**
* “As a [persona], I [want to], [so that].”

* [Article: User Stories with Examples and Template](http://https://www.atlassian.com/agile/project-management/user-stories)

AS A USER, I WANT TO set daily goals (physical, mental, intellectual, and top 5 daily), SO I CAN achieve them along with my team members.

Inspiration: How do you stay motivated remotely with your teammates? We understand the importance of accountability. With "gamified-wellness-tracker", you can set your daily goals along with other team members, earning team points for friendly competition while achieving goals together!

> Focus on building MVP of the project, put stretch goals in the back burner, come back to them later.

**MVP (Minimum Viable Product)**
* Users select Goals and add them to their personal dashboards, UserGoals
* Users can add Notes (specific goals) to each UserGoal
* Users are organized into Teams, compete against other teams

**Stretch Goals**
* Users can mark a goal complete
* Once goals are completed, points will be added to individual points, individual points will be included in the team points
* An admin to organize teams, and make changes
* Motivational quotes randomizer
* User customizable profiles (pump up song, motivational quotes)


#### **STEP 2: Choosing Your Models; Modeling Your Data**

* What are all the models associated with my app?

* How are they related to one another?

* [Video: Jennifer Hansen's MyBlog Series (Planning Object Relationships)](http://https://www.youtube.com/watch?v=825w5S69J38)

#### **STEP 3: Diagraming Your Schema**
* Use [Draw.io](http://https://app.diagrams.net/) to display your data above *visually* by diagramming your schema.

* [Video: Creating Entity Relationship Diagrams using Draw.io](http://https://www.youtube.com/watch?v=lAtCySGDD48)

* [My Example: Rails Project Entity Relationship Diagram](https://viewer.diagrams.net/?highlight=0000ff&edit=_blank&layers=1&nav=1&title=Rails%20Final%20ERD#R7V1tc5s4EP41nrl%2BSId344%2Bxk7TTJnOdtDfX%2B5SRQcZMMOKEnDj3608CAQbhBGxs4ZcZTwuLEGKf1cNqpVUG%2BmSx%2BoJBNH9ALgwGmuKuBvrNQNNURdMG7Ke4b6nE0IepwMO%2BywsVgp%2F%2BfzC7k0uXvgvjUkGCUED8qCx0UBhCh5RkAGP0Wi42Q0H5qRHwoCD46YBAlP7tu2SeSm1TKeRfoe%2FNsyerCr%2ByAFlhLojnwEWvJRFckTsUEt7EHxAvQAhDQq88APwM8cC8nRPC3vR6oN3R34yV%2Fuwh5AUQRH782UELKnZiWuRuBhZ%2BwNS8VtGYV0Qfp98O9AlGiKRHi9UEBgyrDIa0TXcbruZ6wKzeBjdMlAf3ZvqMv31TJ%2Bpy%2BHUUj26vMrW9gGDJFTzQrIBWOF6ym2PyxhVv%2FbtkLR0TqqMrEPhemChBCeCM6YdeYZbALvqhmzSJXVWiVX5xCpxnD6Nl6F45KEA4LYG96R%2BaYbNS2oT%2Bqxmj4thUPhVPpkce%2Fz9pYOBXJa7%2FUtvmd55smmtPKx1%2Fyhse%2BCG8mnOjYneqFnutTe1KWlEWxREIa1u21pyBpiuKqtiKWPMcxE%2FUgN6y6ijIaY35U8AiogfhNI62eaqizGY176NfL2OInzwEgnjzozNxzWtvlIrQbQCzvRoZqkqOo2oVh5pdY0x7VG25JUrFtmq0%2Fb6iJ4drC5nTzuLNk1vlq2V3IzyYuX34Nh%2FVvCNTbd8PpjBAoRc%2FEfSBkndRilK0dNsXrdForSW2bX1n7dGvCQSLD5oxxTVWuqNJUyH7ZGdCrfSaGvsyU%2Fnr3CfwZwQcJn6lHiKjQLII6Jma37buU3A34wViWsOaiPsYXyBaQIIpfSr8qpnewL1LzeYOxmvhq%2BmZRzZf89OGXAa47%2BXlFRcuDT3gXk0LD2eoCh7OF8olgoKoNxixQwKmTDSOCcCEu7%2B6kth3SAD1BDDXFTWTAESxnxRPJXM%2FcO%2FBG1qSrKLsbDzzV9B9TL1fVpY6wve0MnbKKmd%2B5E%2FeGHaZO1g3DgWCPXGMYUzbcg9iwkvM%2FCCYpJZKm6%2FPZjPNcZJ2Y%2FQM16641tQyrW7AtXSlBK9uCeiqdg26qr43eLUaB3YDtPTViQ%2BCRzosAaGXoFwGkSHhYhT9AtiDhAsi5DMMbl9gOjBQKsoPUchqIijiFxOPOD2cIkLogIBDzvWRV5rowhzTH6MU5bM5MG8Yt5hjtTinP1YckwkKKbbUAlkdkBrCK4xJLazv94OPwc7AFbtuLbj7w1YXsP3xvR26yRgUFOi2Bk6pAFftqIjqcxYkw8i579KBTwtEtMaIlNjzkAgYAgLMEXuiN8mFIePHtCz7rDt%2B6N2nd1rScFpt7jnmQXEzj4IVq6geAyta0lnR2hHbzjsjdP2svl27mtkYDmmUOBTU7wACPcTr7jEn1gFT5snOUeoNIdoXQtwTIY6kE%2BLohAnRbgyHLELMsF5TvwtjB%2FsR8VF4NpzYHKi%2BcKImfsn%2BitOpqVOKjEDVNeGwLjIysoY66CgyYmwXGMlnHrtH9zi%2BePIDI3k3OJ7AiCZ%2B8U4pMKL1%2F6Onix%2B9ZJrqrAIjLXDqyzdPF2cD%2BsiK8scB7VlRemBE33UqoMfjAL25QyKNEsVoPaPEECxg3zmxq0FAC5R6Q4hihP9CiN0QovTAiL7rLECfCdFoDIc0QhQD9TMfx%2BTprCixOU69oUQxLnKhxG4oUdWkc%2BKuYZE%2Bc2JzPKRxohi5CMC5UWJzmPpCiYZxYcCOGNCUzYCGeTKEZ%2FTfCTREJzACcfyKcO8jhV3xXQuU%2BsJ31vDCdx3xXc0C8MPynSV6fHeyJ0saUOA2Pc3qvwNoiQ4gy5c4gokTCSD1hQ6z5IwNWaLHkZZ5zDmYHWa%2BNUoTWksJKq%2Ba4F2rprdV%2Bg%2Bzbt8BwTUXL2iXSbpuXQZSYgPQ5T1R7Eftk5DKqzHMbMXiWg%2FKE9pLeSr76kGqIs6OHF8X6j6zuUna4R771almNe9VrVvlNV8IrN0nv7KeLF9fJpHB6mYKLwx22ZvhLPZmeN8Lu%2BzNcPFQW3qodpng1ZrVAlrdIG9vBG%2BKS%2BN%2BJTsZbBiWH%2BlycNeEtmsIZkOv2NpUtzpaDj4so2s0XTK8v0R5U6v5fPcvxil%2FPbjZHOy%2BrAc3TztRPjfd%2FoY1TdE5PpKwphyc%2BhLZNC%2BJ8vtiRenrwc0TTpQ3%2B58ob4rL6BJKPKelPi1g6g0jHkfe4DEyovQF4eYJZ8qb%2FU8azL6IVUbktnsunHh8WYOq0sBNhK4HM11QDfjk7REGgO2BcFtcSTWWBktUrRzHgqF7zTbIpqe3j%2F9BjH6hBxb95CGW4toChO6fCcRw5ZPf2e30%2BB8GJqW59OxmlfUydvKWnYTZrt52JXrDzl0Qz5M417vbQcZoiR34HshcPyQj%2Fo19gnsJTHtNO61at4FkLsSJ1l9gqcF1JsGf8YP1vjVjqwTmDKViVem787sKwxIqMioV6dWKUt0IFSUWmr%2F4LkbbwP89DaOlLcdvv%2FOi9GStTnZaVJqcZbVub99Z6vOH9m3bPbfvfIfWtvZdrWh0aPNukKYjxbzfNdXtTS7bhvBDkxupPTM5Y1QxuWw5TluTs7RKRQe2OXvTjjnKKW4p7AJoz2q3FLYcG05n71nz9isdmoaNVGtf3p59GQE38%2BTt49s5x67fOWdy911th3Gf50vsrYbC1iFxGIlD4fPbP6cFTqvBRnLUDorbceyfI38WuT03Sp8vGWmbuFF2lLDDPjdq7qBI40ZxNv%2F8Nl1vgVNvuPGylc6%2BuFH6zMnohLfSGW2VRX1YShRDmQ5aRAEkZzOV3AKlvhBiHj%2B6EOCuBCh%2F4xxVkT1C7o7xcsPsMeWpiuiOh4jAs5knbgPS%2FhmPnhZ%2FqjeNJxd%2FX1m%2F%2FR8%3D)

#### **STEP 4: Wireframing**
* [Low Fidelity Wireframes](http://https://www.youtube.com/watch?v=rTox2mQfYFI)

* An easy to use wireframing site: [Figma](http://www.figma.com/)

> A quote that I kept in mind while working through Rails project: 
> "1. make it work, 2. make it fast, 3. then make it pretty!"

