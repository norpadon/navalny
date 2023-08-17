# Attempt to independently replicate the stylometric study of Navalny's prison texts

Original article in Kyiv Post: https://www.kyivpost.com/analysis/20577

## Data

### Sources
Data was collected from the following sources:
| Source               | Source url                             | Number of posts |
| ---------------------|----------------------------------------|-----------------|
| Navalny's Blog       | https://navalny.com                    | 2978            |
| Navalny's Telegram   | https://t.me/navalny                   | 3152            |
| Navalny's Instagram  | https://instagram.com/navalny          | 2023            |
| Volkov's LiveJournal | https://leonwolf.livejournal.com       | 402             |
| Volkov's Telegram    | https://t.me/leonid_volkov             | 3664            |
| Volkov's Instagram   | https://instagram.com/leonidvolkov     | 514             |
| Sobol's LiveJournal  | https://sobollubov.livejournal.com     | 230             |
| Sobol's Telegram     | https://t.me/TeamSobol                 | 14173           |
| Sobol's Instagram    | https://instagram.com/sobollubov       | 2378            |
| Pevchikh's Instagram | https://instagram.com/maria_pevchikh   | 106             |
| Alburov's Instagram  | https://instagram.com/alburov          | 717             |
| Zhdanov's Telegram   | https://t.me/ioannzh                   | 1581            |
| Zhdanov's Instagram  | https://instagram.com/ioannzh          | 658             |
| Yarmysh's Telegram   | https://t.me/Kira_Yarmysh              | 3577            |
| Yarmysh's Instagram  | https://instagram.com/kira_yarmysh     | 363             |
| Navalny's Facebook   | https://facebook.com/navalny           | 624             |
| Volkov's Facebook    | https://facebook.com/leonid.m.volkov   | 664             |
| Sobol's Facebook     | https://facebook.com/soboll.ru         | 920             |
| Alburov's Facebook   | https://facebook.com/alburov           | 37              |
| Zhdanov's Facebook   | https://facebook.com/zhdanovivan       | 490             |

### Structure
`fbk_archive.csv` contains aggregated data as a CSV table with the following columns:
* `author`: Author of the post
* `text`: Contents of the post
* `date`: Date in the format `%Y-%m-%d`
* `url`: Link to the original post
* `source_type`: Link to the source homepage


## Disclamers and conflicts of interest
Author (Artur Chakhvadze) is not in any way affiliated with Navalny, FBK, ACF international, Kyiv Post or Oleksiy Borovskiy.

Anna Vellikok, a relative of Georgy Alburov, has promised to buy a beer to the Author as a token of gratitude for replicating the study.

Author does not hold any credentials whatsoever, contents of this repository should be judged on their own merits.
