# Thursday Trivia Memory Log
_Tracks previously used questions to avoid repetition. Updated automatically each week. Rolling window: ~12 weeks._

---

## ⚙️ Run Settings (read these EVERY run — they override skill defaults)

| Setting | Value | Notes |
|---------|-------|-------|
| Archive window | **7 files** (current + 6 previous) | Retain 7 total; prune anything older |
| Archive nav pills | **"Today" pill + current date pill + 6 previous** | "Today" always links to ./index.html (home button, works from any historical page). Then current date as first archive pill (dim style, links to dated file). Then 5 more previous dated pills. 8 pills total. |
| Today pill style | `color:#fff; background:rgba(255,255,255,0.22); border:1px solid rgba(255,255,255,0.4); font-weight:700` | Bright/bold. Label always "Today". Links to ./index.html. Appears first, before all dated pills. |
| Archive pill style | `color:rgba(255,255,255,0.75); background:rgba(255,255,255,0.08); border:1px solid rgba(255,255,255,0.15); font-weight:600` | Standard dim style |
| Cleanup keep count | **7** | Use `tail -7` in Step 7 cleanup |
| Reds record source | **MLB Stats API only** — use `https://statsapi.mlb.com/api/v1/standings?leagueId=104&season=YYYY&standingsTypes=regularSeason&hydrate=team` and `https://statsapi.mlb.com/api/v1/schedule?teamId=113&season=YYYY&startDate=YYYY-MM-DD&endDate=YYYY-MM-DD&sportId=1&hydrate=linescore,team` (fetch via python/curl in bash, never rely on web search snippets for the record) | Web search snippets give stale/wrong records |
| Required section: Movies This Weekend | **Always include — subsection inside Box Office card** | Do NOT create a separate card. Add a dashed-border subsection at the bottom of the existing Box Office card. Label: `Coming This Weekend (Month D–D)`. Search for wide releases opening that weekend. List 3–4 films: bold title, director/star, one-line premise. |
| Required section: Song & Artist 1990–2010 | **Always include — song-row format with play links** | Do NOT use Q&A format. Use `song-row` CSS layout: song title (bold, 14px), artist · year · album (small, muted) on the left; Spotify (green) + Apple Music (red) pill buttons on the right. Search `site:open.spotify.com/track "[Song Title]" [Artist]` and `site:music.apple.com/us/song "[Song Title]" [Artist]` to get verified track IDs. 5–6 songs per run. Check music memory log to avoid repeats. Required CSS: `.song-row{display:flex;justify-content:space-between;align-items:center;padding:8px 0;border-bottom:1px dashed rgba(255,255,255,0.15);gap:8px;} .song-row:last-of-type{border-bottom:none;} .song-info{flex:1;min-width:0;} .song-title{font-weight:700;font-size:14px;color:#e8e8f0;} .song-meta{font-size:12px;color:rgba(255,255,255,0.55);margin-top:1px;} .song-links{display:flex;gap:6px;flex-shrink:0;} .song-links a{text-decoration:none;font-size:11px;font-weight:700;padding:4px 9px;border-radius:4px;white-space:nowrap;} .song-links a.spotify{background:#1db954;color:#fff;} .song-links a.apple{background:#fa233b;color:#fff;}` |

---

## 📍 Capitals Used

| Week | Question | Answer |
|------|----------|--------|
| Aug 31 | Canada | Ottawa (chosen by Queen Victoria 1857 as Toronto/Montreal compromise) |
| Aug 31 | Turkey | Ankara (not Istanbul; moved 1923) |
| Aug 31 | Belize | Belmopan (built inland after Hurricane Hattie, 1961; ~20,000 people) |
| Aug 31 | Switzerland | Bern ("federal city"; no constitutional capital) |
| Aug 28 | Bhutan | Thimphu (only national capital with no traffic lights) |
| Aug 28 | Iceland | Reykjavík (northernmost capital of a sovereign state; "smoky bay") |
| Aug 28 | Ecuador | Quito (~9,350 ft; one of first two UNESCO World Heritage cities, 1978) |
| Aug 28 | Vietnam | Hanoi (not Ho Chi Minh City) |
| Aug 27 | Azerbaijan | Baku (lowest-lying national capital, ~92 ft below sea level) |
| Aug 27 | Colombia | Bogotá (~8,660 ft elevation) |
| Aug 27 | Jordan | Amman (built on seven hills; Roman-era Philadelphia) |
| Aug 27 | Papua New Guinea | Port Moresby |
| Aug 26 | Croatia | Zagreb |
| Aug 26 | Paraguay | Asunción (founded 1537, one of South America's oldest cities) |
| Aug 26 | Malaysia | Kuala Lumpur (Putrajaya is administrative seat) |
| Aug 26 | Senegal | Dakar (finish of the old Paris–Dakar Rally) |
| Aug 25 | Uruguay | Montevideo (independence declared Aug 25, 1825) |
| Aug 25 | Slovenia | Ljubljana (dragon on the coat of arms / Dragon Bridge) |
| Aug 25 | Tanzania | Dodoma (moved inland from Dar es Salaam, official 1996) |
| Aug 25 | Sri Lanka | Sri Jayawardenepura Kotte (legislative; Colombo is commercial) |
| Aug 24 | Cambodia | Phnom Penh (confluence of Mekong, Tonlé Sap, Bassac) |
| Aug 24 | Estonia | Tallinn (medieval Old Town, UNESCO site) |
| Aug 24 | Botswana | Gaborone (purpose-built for 1966 independence) |
| Aug 24 | Peru | Lima (founded 1535 by Pizarro, "City of the Kings") |
| Aug 20 | Myanmar | Naypyidaw (purpose-built, capital moved from Yangon 2005) |
| Aug 20 | Bolivia | Sucre (constitutional capital; La Paz is seat of government) |
| Aug 20 | Ghana | Accra |
| Aug 20 | Nepal | Kathmandu |
| Aug 19 | Mongolia | Ulaanbaatar (coldest national capital on Earth) |
| Aug 19 | Morocco | Rabat (not Casablanca/Marrakesh) |
| Aug 19 | New Zealand | Wellington (southernmost capital of a sovereign state) |
| Aug 19 | Kazakhstan | Astana (Nur-Sultan 2019-2022) |


| Jun 18 | Nevada | Carson City |
| Jun 18 | Missouri | Jefferson City |
| Jun 18 | Greece | Athens |
| Jun 18 | Kenya | Nairobi |
| Jun 23 | Utah | Salt Lake City |
| Jun 23 | Poland | Warsaw |
| Jun 23 | Alabama | Montgomery |
| Jun 23 | Philippines | Manila |
| Jun 24 | Arizona | Phoenix |
| Jun 24 | North Carolina | Raleigh |
| Jun 24 | Chile | Santiago |
| Jun 24 | Indonesia | Jakarta |
| Aug 13 | Bhutan | Thimphu |
| Aug 13 | Namibia | Windhoek |
| Aug 13 | Latvia | Riga |
| Aug 13 | Suriname | Paramaribo |
| Aug 17 | Ethiopia | Addis Ababa (HQ of the African Union) |
| Aug 17 | Vietnam | Hanoi |
| Aug 17 | Iceland | Reykjavík (northernmost capital of a sovereign state) |
| Aug 17 | Fiji | Suva (on Viti Levu) |



---

## 📺 Classic TV Used

| Week | Show | Character | Actor |
|------|------|-----------|-------|
| Aug 31 | The Andy Griffith Show (1960–68) | Deputy Barney Fife | Don Knotts |
| Aug 31 | The Munsters (1964–66) | Herman Munster | Fred Gwynne |
| Aug 31 | Dark Shadows (1966–71) | Barnabas Collins | Jonathan Frid |
| Aug 31 | The Rockford Files (1974–80) | Jim Rockford | James Garner |
| Aug 31 | Cheers (1982–93) | Cliff Clavin | John Ratzenberger |
| Aug 31 | Wiseguy (1987–90) | Vinnie Terranova | Ken Wahl |
| Aug 28 | The Beverly Hillbillies (1962–71) | Jed Clampett | Buddy Ebsen |
| Aug 28 | Mission: Impossible (1966–73) | Jim Phelps | Peter Graves |
| Aug 28 | M*A*S*H (1972–83) | Cpl. Maxwell Klinger | Jamie Farr |
| Aug 28 | The Golden Girls (1985–92) | Sophia Petrillo | Estelle Getty |
| Aug 28 | Night Court (1984–92) | Judge Harry Stone | Harry Anderson |
| Aug 28 | Kojak (1973–78) | Lt. Theo Kojak | Telly Savalas |
| Aug 27 | The Twilight Zone (1959–64) | Host/creator | Rod Serling |
| Aug 27 | Rawhide (1959–65) | Rowdy Yates | Clint Eastwood |
| Aug 27 | I Dream of Jeannie (1965–70) | Jeannie | Barbara Eden |
| Aug 27 | Three's Company (1977–84) | Jack Tripper | John Ritter |
| Aug 27 | Family Ties (1982–89) | Alex P. Keaton | Michael J. Fox |
| Aug 27 | Homicide: Life on the Street (1993–99) | Det. Frank Pembleton | Andre Braugher |
| Aug 26 | The Honeymooners (1955–56) | Ed Norton | Art Carney |
| Aug 26 | Perry Mason (1957–66) | Perry Mason | Raymond Burr |
| Aug 26 | The Waltons (1972–81) | John-Boy Walton | Richard Thomas |
| Aug 26 | Charlie's Angels (1976–81) | Sabrina Duncan | Kate Jackson |
| Aug 26 | The A-Team (1983–87) | B.A. Baracus | Mr. T (Laurence Tureaud) |
| Aug 26 | The X-Files (1993–2002) | Dana Scully | Gillian Anderson |
| Aug 25 | Gunsmoke (1955–75) | Marshal Matt Dillon | James Arness |
| Aug 25 | Bewitched (1964–72) | Samantha Stephens | Elizabeth Montgomery |
| Aug 25 | The Odd Couple (1970–75) | Felix Unger | Tony Randall |
| Aug 25 | Taxi (1978–83) | Rev. Jim Ignatowski | Christopher Lloyd |
| Aug 25 | St. Elsewhere (1982–88) | Dr. Donald Westphall | Ed Flanders |
| Aug 25 | Northern Exposure (1990–95) | Chris Stevens | John Corbett |
| Aug 24 | Star Trek (1966–69) | Mr. Spock | Leonard Nimoy |
| Aug 24 | F Troop (1965–67) | Sgt. Morgan O'Rourke | Forrest Tucker |
| Aug 24 | The Jeffersons (1975–85) | George Jefferson | Sherman Hemsley |
| Aug 24 | Knots Landing (1979–93) | Karen Fairgate MacKenzie | Michele Lee |
| Aug 24 | Murder, She Wrote (1984–96) | Jessica Fletcher | Angela Lansbury |
| Aug 24 | Married... with Children (1987–97) | Al Bundy | Ed O'Neill |
| Aug 20 | Bonanza (1959–73) | Ben Cartwright | Lorne Greene |
| Aug 20 | Get Smart (1965–70) | Maxwell Smart / Agent 86 | Don Adams |
| Aug 20 | WKRP in Cincinnati (1978–82) | Dr. Johnny Fever | Howard Hesseman |
| Aug 20 | Hogan's Heroes (1965–71) | Col. Wilhelm Klink | Werner Klemperer |
| Aug 20 | Hill Street Blues (1981–87) | Capt. Frank Furillo | Daniel J. Travanti |
| Aug 20 | Twin Peaks (1990–91) | Special Agent Dale Cooper | Kyle MacLachlan |
| Aug 19 | Green Acres (1965–71) | Oliver Wendell Douglas | Eddie Albert |
| Aug 19 | The Fugitive (1963–67) | Dr. Richard Kimble | David Janssen |
| Aug 19 | Barney Miller (1975–82) | Capt. Barney Miller | Hal Linden |
| Aug 19 | Dallas (1978–91) | J.R. Ewing | Larry Hagman |
| Aug 19 | Magnum, P.I. (1980–88) | Jonathan Higgins | John Hillerman |
| Aug 19 | Quantum Leap (1989–93) | Adm. Al Calavicci | Dean Stockwell |





| Jun 18 | The Rifleman (1958–63) | Lucas McCain | Chuck Connors |
| Jun 18 | Maverick (1957–62) | Bret Maverick | James Garner |
| Jun 18 | Maude (1972–78) | Maude Findlay | Bea Arthur |
| Jun 18 | The Love Boat (1977–86) | Capt. Merrill Stubing | Gavin MacLeod |
| Jun 18 | Falcon Crest (1981–90) | Angela Channing | Jane Wyman |
| Jun 18 | Benson (1979–86) | Benson DuBois | Robert Guillaume |
| Jun 23 | Petticoat Junction (1963–70) | Kate Bradley | Bea Benaderet |
| Jun 23 | Have Gun – Will Travel (1957–63) | Paladin | Richard Boone |
| Jun 23 | Dark Shadows (1966–71) | Barnabas Collins | Jonathan Frid |
| Jun 23 | Kung Fu (1972–75) | Kwai Chang Caine | David Carradine |
| Jun 23 | Soap (1977–81) | Jessica Tate | Katherine Helmond |
| Jun 23 | Cannon (1971–76) | Frank Cannon | William Conrad |
| Jun 24 | Leave It to Beaver (1957–63) | Ward Cleaver | Hugh Beaumont |
| Jun 24 | Gomer Pyle, U.S.M.C. (1964–69) | Gomer Pyle | Jim Nabors |
| Jun 24 | The Partridge Family (1970–74) | Shirley Partridge | Shirley Jones |
| Jun 24 | The Streets of San Francisco (1972–77) | Det. Lt. Mike Stone | Karl Malden |
| Jun 24 | Baretta (1975–78) | Det. Tony Baretta | Robert Blake |
| Jun 24 | The Phil Silvers Show (1955–59) | Sgt. Ernie Bilko | Phil Silvers |
| Aug 13 | The Andy Griffith Show (1960-68) | Deputy Barney Fife | Don Knotts |
| Aug 13 | The Wild Wild West (1965-69) | James West | Robert Conrad |
| Aug 13 | All in the Family (1971-79) | Archie Bunker | Carroll O'Connor |
| Aug 13 | Banacek (1972-74) | Thomas Banacek | George Peppard |
| Aug 13 | Cheers (1982-93) | Sam Malone | Ted Danson |
| Aug 13 | Moonlighting (1985-89) | Maddie Hayes | Cybill Shepherd |
| Aug 17 | Columbo (1971–2003) | Lt. Columbo | Peter Falk |
| Aug 17 | The Mary Tyler Moore Show (1970–77) | Lou Grant | Ed Asner |
| Aug 17 | The Untouchables (1959–63) | Eliot Ness | Robert Stack |
| Aug 17 | Sanford and Son (1972–77) | Fred Sanford | Redd Foxx |
| Aug 17 | Miami Vice (1984–90) | Det. Sonny Crockett | Don Johnson |
| Aug 17 | The Six Million Dollar Man (1974–78) | Steve Austin | Lee Majors |


---

## 🎨 Arts & Literature Used

| Week | Topic / Question | Answer |
|------|-----------------|--------|
| Aug 31 | The Canterbury Tales author | Geoffrey Chaucer (begun c. 1387, Middle English, unfinished) |
| Aug 31 | Girl with a Pearl Earring (c.1665) painter | Johannes Vermeer |
| Aug 31 | The Four Seasons (1725) composer | Antonio Vivaldi ("the Red Priest") |
| Aug 31 | "the clocks were striking thirteen" opener | Nineteen Eighty-Four — George Orwell |
| Aug 31 | Paradise Lost (1667) poet | John Milton (blind, dictated; sold for £10) |
| Aug 31 | The Handmaid's Tale (1985) author | Margaret Atwood |
| Aug 28 | Frankenstein (1818) author | Mary Shelley (started at 18, "year without a summer") |
| Aug 28 | The Scream (1893) painter | Edvard Munch |
| Aug 28 | "In the Hall of the Mountain King" / Peer Gynt composer | Edvard Grieg (1875) |
| Aug 28 | Things Fall Apart (1958) author | Chinua Achebe (title from Yeats) |
| Aug 28 | Leaves of Grass poet | Walt Whitman |
| Aug 28 | Death of a Salesman (1949) playwright | Arthur Miller (Pulitzer 1949) |
| Aug 27 | "Beauty is truth, truth beauty" / Ode on a Grecian Urn poet | John Keats |
| Aug 27 | The Night Watch (1642) painter | Rembrandt van Rijn |
| Aug 27 | Boléro (1928) composer | Maurice Ravel |
| Aug 27 | To Kill a Mockingbird (1960) author | Harper Lee (Pulitzer 1961) |
| Aug 27 | Waiting for Godot (1953) playwright | Samuel Beckett |
| Aug 27 | The Color Purple (1982) author | Alice Walker |
| Aug 26 | The Bell Jar (1963) author | Sylvia Plath (pen name Victoria Lucas) |
| Aug 26 | Guernica (1937) painter | Pablo Picasso |
| Aug 26 | "Rhapsody in Blue" (1924) composer | George Gershwin |
| Aug 26 | Catch-22 (1961) author | Joseph Heller |
| Aug 26 | The Thinker / The Kiss sculptor | Auguste Rodin |
| Aug 26 | "Because I could not stop for Death" poet | Emily Dickinson |
| Aug 25 | "Call me Ishmael" opener | Moby-Dick (1851) — Herman Melville |
| Aug 25 | American Gothic (1930) painter | Grant Wood |
| Aug 25 | Symphony No. 5 in C minor composer | Ludwig van Beethoven (1808) |
| Aug 25 | Nighthawks (1942) painter | Edward Hopper |
| Aug 25 | Brave New World (1932) author | Aldous Huxley |
| Aug 25 | A Streetcar Named Desire (1947) playwright | Tennessee Williams |
| Aug 24 | "In a hole in the ground there lived a hobbit" | The Hobbit — J.R.R. Tolkien (1937) |
| Aug 24 | The Birth of Venus (painting) | Sandro Botticelli, c. 1485, Uffizi |
| Aug 24 | "The Blue Danube" waltz | Johann Strauss II (1866) |
| Aug 24 | The Son of Man (bowler hat, green apple) | René Magritte |
| Aug 24 | Their Eyes Were Watching God (1937) | Zora Neale Hurston |
| Aug 24 | Fathers and Sons (1862), popularized "nihilist" | Ivan Turgenev |
| Aug 20 | Wuthering Heights (1847) author | Emily Brontë (pen name Ellis Bell) |
| Aug 20 | The Starry Night (1889) painter | Vincent van Gogh |
| Aug 20 | "Ride of the Valkyries" / Ring cycle composer | Richard Wagner (Die Walküre) |
| Aug 20 | Invisible Man (1952) author | Ralph Ellison |
| Aug 20 | "The Road Not Taken" poet | Robert Frost |
| Aug 20 | One Hundred Years of Solitude (1967) author | Gabriel García Márquez (Macondo) |
| Aug 19 | "It is a truth universally acknowledged…" opener | Pride and Prejudice (1813) — Jane Austen |
| Aug 19 | The Persistence of Memory (1931) painter | Salvador Dalí |
| Aug 19 | 1812 Overture composer | Pyotr Ilyich Tchaikovsky |
| Aug 19 | The Grapes of Wrath (1939) author | John Steinbeck |
| Aug 19 | "The Raven" (1845) poet | Edgar Allan Poe |
| Aug 19 | "Happy families are all alike…" opener | Anna Karenina — Leo Tolstoy |




| Jun 18 | Dracula (1897) author | Bram Stoker |
| Jun 18 | Little Women author | Louisa May Alcott |
| Jun 18 | "Clair de Lune" composer | Claude Debussy |
| Jun 18 | Gulliver's Travels (1726) author | Jonathan Swift |
| Jun 18 | The Little Mermaid / Ugly Duckling author | Hans Christian Andersen |
| Jun 18 | Fahrenheit 451 author | Ray Bradbury |
| Jun 23 | The Scarlet Letter (1850) author | Nathaniel Hawthorne |
| Jun 23 | The Canterbury Tales author | Geoffrey Chaucer |
| Jun 23 | Gone with the Wind (1936) author | Margaret Mitchell |
| Jun 23 | The Garden of Earthly Delights painter | Hieronymus Bosch |
| Jun 23 | "The Planets" suite composer | Gustav Holst |
| Jun 23 | "Howl" (1956) poet | Allen Ginsberg |
| Jun 24 | The Handmaid's Tale (1985) author | Margaret Atwood |
| Jun 24 | A Doll's House (1879) playwright | Henrik Ibsen |
| Jun 24 | De Stijl grid abstraction painter | Piet Mondrian |
| Jun 24 | "Carmina Burana" (1936) composer | Carl Orff |
| Jun 24 | Oedipus Rex tragedian | Sophocles |
| Jun 24 | Dune (1965) author | Frank Herbert |
| Aug 13 | Crime and Punishment (1866) author | Fyodor Dostoevsky |
| Aug 13 | Girl with a Pearl Earring (c.1665) painter | Johannes Vermeer |
| Aug 13 | The Four Seasons (c.1725) composer | Antonio Vivaldi |
| Aug 13 | "Do I dare to eat a peach?" / Prufrock poet | T.S. Eliot |
| Aug 13 | Slaughterhouse-Five (1969) author | Kurt Vonnegut |
| Aug 13 | Sculptor of David (1504) / Sistine ceiling | Michelangelo |
| Aug 17 | The Old Man and the Sea (1952) author | Ernest Hemingway |
| Aug 17 | "It was the best of times…" opener | A Tale of Two Cities — Charles Dickens |
| Aug 17 | The Great Wave off Kanagawa (c.1831) printmaker | Katsushika Hokusai |
| Aug 17 | "New World" Symphony No. 9 (1893) composer | Antonín Dvořák |
| Aug 17 | "Do not go gentle into that good night" poet | Dylan Thomas |
| Aug 17 | Beloved (1987) author | Toni Morrison |


---

## 🧩 General Trivia Topics Used

| Week | Category | Topic/Fact |
|------|----------|-----------|
| Aug 31 | Science | Glass is an amorphous solid, not a slow-flowing liquid |
| Aug 31 | Space | More trees on Earth (~3T) than stars in the Milky Way (100–400B) |
| Aug 31 | Geography | Africa is the only continent in all four hemispheres |
| Aug 31 | Animals | A group of flamingos is a "flamboyance" |
| Aug 31 | Body | The human nose can distinguish ~1 trillion smells |
| Aug 31 | Food | A pineapple plant takes ~2 years to make one fruit; once rented for parties |
| Aug 31 | Language | "Set" has the most OED definitions (400+) |
| Aug 31 | History | Anglo-Zanzibar War 1896 — shortest war, ~38 minutes |
| Aug 31 | History | Great Fire of London 1666 — 13,200 houses lost, official death toll six |
| Aug 31 | Sports | Golf ball dimples came from nicked balls flying farther |
| Aug 31 | Pop Culture | Nintendo Wii's development codename was "Revolution" |
| Aug 31 | Local (Cincinnati) | Music Hall (1878) built over a potter's field; remains found in renovations |
| Aug 31 | Reds bar-bet | Johnny Vander Meer — only back-to-back no-hitters in MLB history (Jun 11 & 15, 1938) |
| Aug 28 | Science | Bananas are slightly radioactive (potassium-40); "banana equivalent dose" |
| Aug 28 | Space | A day on Venus (243 Earth days) is longer than its year (225) |
| Aug 28 | Geography | Russia spans 11 time zones |
| Aug 28 | Animals | A shrimp's heart is in its head |
| Aug 28 | Body | Stomach lining replaces itself every 3–4 days |
| Aug 28 | Food | Carrots were originally purple; orange bred by 17th-c. Dutch growers |
| Aug 28 | Language | The dot over a lowercase i/j is a "tittle" |
| Aug 28 | History | Oxford (teaching by 1096) is older than the Aztec Empire (1325) |
| Aug 28 | Sports | Two basketballs fit side by side through an 18-inch rim |
| Aug 28 | Pop Culture | "Wilhelm scream" (1951, Distant Drums) reused in 400+ films |
| Aug 28 | Did You Know | Scotland's national animal is the unicorn |
| Aug 28 | Local (Cincinnati) | Roebling Suspension Bridge (1866) longest in world at opening; Brooklyn Bridge prototype |
| Aug 28 | Reds bar-bet | Named "Reds" because the 1869 Red Stockings first wore knee pants w/ visible red socks |
| Aug 27 | Space | Neptune completed only one orbit since its 1846 discovery (finished 2011) |
| Aug 27 | Science | Helium found in space (Sun spectrum, 1868) before it was found on Earth |
| Aug 27 | Geography | Alaska has more coastline than the other 49 states combined |
| Aug 27 | Animals | Cows form best friendships; stressed when separated |
| Aug 27 | Body | Corneas have no blood supply — oxygen straight from the air |
| Aug 27 | Food | Vanilla 2nd-most expensive spice after saffron; ~80% from Madagascar |
| Aug 27 | Language | "Dreamt" is the only common English word ending in -mt |
| Aug 27 | History | Anne Frank and MLK Jr. were both born in 1929 |
| Aug 27 | Math | More ways to shuffle 52 cards (52!) than atoms making up the Earth |
| Aug 27 | Sports | NHL pucks are frozen before games so they slide instead of bounce |
| Aug 27 | Pop Culture | Mario debuted as "Jumpman" in Donkey Kong (1981) — a carpenter, not a plumber |
| Aug 27 | Local (Cincinnati) | Abandoned subway under Central Parkway — 2+ mi of 1920s tunnels, never used |
| Aug 27 | Reds bar-bet | Oldest pro franchise — Reds traditionally open every season at home |
| Aug 26 | Science | Octopuses have three hearts and blue blood (hemocyanin) |
| Aug 26 | Geography | Parts of Atacama Desert have no recorded rainfall ever |
| Aug 26 | Space | Apollo footprints on the Moon will last millions of years |
| Aug 26 | Animals | A group of giraffes is a "tower" |
| Aug 26 | Body | Roughly as many bacterial cells as human cells (~1.3:1) |
| Aug 26 | Food | Ripe cranberries bounce — sorted with "bounce boards" |
| Aug 26 | Language | "Pineapple" meant pine cone first; fruit named for resemblance |
| Aug 26 | History | Reagan was a Rock River lifeguard credited with 77 rescues |
| Aug 26 | Sports | NFL was the American Professional Football Association until 1922 |
| Aug 26 | Pop Culture | Windows XP "Bliss" wallpaper is an unretouched Sonoma County photo |
| Aug 26 | Did You Know | Peanut butter can be turned into diamond under extreme pressure |
| Aug 26 | Local (Cincinnati) | Over-the-Rhine has one of the largest intact Italianate collections in the US |
| Aug 26 | Reds bar-bet | Reds were first MLB team to fly to a road game — Cincinnati→Chicago, June 8, 1934 |
| Aug 25 | Science | Honey never spoils — 3,000-yr-old edible honey in Egyptian tombs |
| Aug 25 | Geography | Canada holds ~62% of the world's lakes |
| Aug 25 | Space | Saturn's density (0.69 g/cm³) is less than water — it would float |
| Aug 25 | Animals | A group of hedgehogs is an "array" |
| Aug 25 | Animals | Wombat droppings are cube-shaped (varying intestinal elasticity) |
| Aug 25 | Body | Brain = ~2% of body weight but ~20% of oxygen/calories |
| Aug 25 | Food | Nutmeg is hallucinogenic and toxic in large doses (myristicin) |
| Aug 25 | Language | "Queue" sounds identical with the last four letters removed |
| Aug 25 | Sports | Marathon 26.2 mi fixed at the 1908 London Olympics for the royal box |
| Aug 25 | History | Last Civil War widow died 2020 — Helen Viola Jackson, 101 |
| Aug 25 | Pop Culture | Mickey Mouse's voice (Wayne Allwine) married Minnie's (Russi Taylor), 1991 |
| Aug 25 | Local (Cincinnati) | Union Terminal rotunda modeled as the Hall of Justice in Super Friends |
| Aug 25 | Local (Cincinnati) | Rod Serling wrote for WLW/WKRC in Cincinnati; quit in 1955 over script censorship |
| Aug 25 | Reds bar-bet | 1976 Reds only team to go undefeated through a full postseason (7–0) |
| Aug 24 | Animals | Group of pandas = "embarrassment"; otters romp/raft |
| Aug 24 | Science | Venus flytrap counts — needs 2 trigger touches in ~20 sec |
| Aug 24 | History | Krakatoa 1883 loudest recorded sound, heard 3,000 mi away |
| Aug 24 | Nature | Methuselah bristlecone pine ~4,800 years old |
| Aug 24 | Language | "Robot" from Czech robota, Čapek's R.U.R. (1920) |
| Aug 24 | Everyday | Shoelace tip = aglet |
| Aug 24 | Weather | Largest snowflake on record 15" — Fort Keogh, MT, 1887 |
| Aug 24 | Geography | Mount Everest grows ~4 mm/year |
| Aug 24 | Food | Cheese is the most stolen food in the world (~4%) |
| Aug 24 | Sports | Olympic ring colors chosen to cover every 1913 national flag |
| Aug 24 | Pop Culture | Lightsaber hum = projector motor + TV interference (Ben Burtt) |
| Aug 24 | Local | Cincinnati has 400+ public outdoor staircases |
| Aug 24 | Reds bar-bet | Frank Robinson only player to win MVP in both leagues (1961 NL / 1966 AL) |
| Aug 20 | Science | Sharks (~400M yrs) are older than trees (~350M yrs) |
| Aug 20 | Space | More trees on Earth (~3 trillion) than stars in the Milky Way (~100–400 billion) |
| Aug 20 | Geography | Maine is the only US state with a one-syllable name |
| Aug 20 | Language | "Bookkeeper" — only common English word with three consecutive double letters |
| Aug 20 | Animals | A group of ferrets is a "business" |
| Aug 20 | Food | Fortune cookies were invented in California, not China |
| Aug 20 | History | Shortest war on record: Anglo-Zanzibar War 1896, ~38 minutes |
| Aug 20 | Body | Fingernails grow ~4× faster than toenails |
| Aug 20 | Sports | Olympics awarded medals for art competitions 1912–1948 |
| Aug 20 | Pop Culture | James Earl Jones uncredited as Darth Vader's voice in first two Star Wars films |
| Aug 20 | Local (Cincinnati) | WLW ran 500,000 watts 1934–39 — most powerful US station ever licensed |
| Aug 20 | Local (Cincinnati) | Roebling Suspension Bridge (1866) world's longest at opening; Roebling then designed the Brooklyn Bridge |
| Aug 20 | Reds bar-bet | Johnny Vander Meer — only back-to-back no-hitters in MLB history (June 11 & 15, 1938) |
| Aug 19 | Science | Bananas are slightly radioactive (potassium-40); "banana equivalent dose" |
| Aug 19 | Astronomy | Venus rotates backwards; its day (243 Earth days) is longer than its year (225) |
| Aug 19 | Geography | Vatican City smallest country, ~0.19 sq mi |
| Aug 19 | Language | "Set" has the most OED definitions (~430) |
| Aug 19 | Animals | A group of porcupines is a "prickle" |
| Aug 19 | Food | Worcestershire sauce contains fermented anchovies |
| Aug 19 | History | Harvard founded 1636, ~30 yrs before calculus was invented |
| Aug 19 | Sports | A smooth golf ball flies about half as far as a dimpled one |
| Aug 19 | Pop Culture | Wilhelm Scream recorded 1951 for Distant Drums; used in 400+ films |
| Aug 19 | Did You Know | Scotland's national animal is the unicorn |
| Aug 19 | Biology | Humans share ~60% of DNA with bananas |
| Aug 19 | Local (Cincinnati) | Cincinnati was "Porkopolis" — biggest US pork-packing center in the 1830s–40s |
| Aug 19 | Reds bar-bet | 1869 Cincinnati Red Stockings — first openly all-salaried pro team; undefeated (~57–0–1) |



| Jun 18 | Science | Teaspoon of neutron-star material ≈ 6 billion tons |
| Jun 18 | Geography | Russia spans 11 time zones (most of any country) |
| Jun 18 | Food | Carrots were originally purple; orange bred in the Netherlands |
| Jun 18 | Animals | A group of crows is a "murder" |
| Jun 18 | History | Oxford (teaching by 1096) older than Aztec Empire (1325) |
| Jun 18 | Body | Stomach grows a new lining every few days |
| Jun 18 | Astronomy | More stars in the universe than grains of sand on Earth's beaches |
| Jun 18 | Geography | Sahara Desert ≈ size of the continental US |
| Jun 18 | Food | Peanuts are legumes, not nuts |
| Jun 18 | Animals | A shrimp's heart is in its head |
| Jun 18 | Language | The dot over i/j is a "tittle" |
| Jun 18 | History | Great Pyramid was tallest structure for ~3,800 years |
| Jun 24 | Animals | Sea otters store a favorite rock in a skin pouch under the forearm |
| Jun 24 | Geography | Istanbul is the only major city on two continents (Europe & Asia) |
| Jun 24 | Science | Hottest air temp on record: 134°F, Death Valley (1913) |
| Jun 24 | Food | A honeybee visits ~2 million flowers per pound of honey |
| Jun 24 | Animals | A group of jellyfish is a "smack" |
| Jun 24 | History | The Hundred Years' War lasted 116 years (1337–1453) |
| Jun 24 | Body | Adult body holds enough iron to make a ~3-inch nail |
| Jun 24 | Astronomy | One day on Mercury lasts ~176 Earth days |
| Jun 24 | Language | No perfect rhyme for month, orange, silver, purple |
| Jun 24 | Food | Tomatoes once feared as "poison apples" (lead from pewter plates) |
| Jun 24 | Science | Glass is an "amorphous solid" |
| Jun 24 | Animals | A blue whale's tongue can weigh as much as an elephant |
| Aug 13 | Trivia | Guinness Book of Records invented 1954 to settle pub arguments |
| Aug 13 | Geography | Alaska is both westernmost AND easternmost US state (Aleutians cross 180th meridian) |
| Aug 13 | Language | "Avocado" from Nahuatl ahuacatl, which also meant "testicle" |
| Aug 13 | Sports | Stanley Cup misspellings never corrected - 1972 "BQSTQN BRUINS" |
| Aug 13 | Food | Ketchup sold as medicine in the 1830s - "tomato pills" |
| Aug 13 | Body | You're ~1 cm taller in the morning - spinal discs compress |
| Aug 13 | Space | Astronauts say space smells like seared steak / spent gunpowder |
| Aug 13 | History | Wyoming gave women the vote in 1869, 51 yrs before the 19th Amendment |
| Aug 13 | Animals | A group of flamingos is a "flamboyance" |
| Aug 13 | Science | A teaspoon of healthy soil holds more microorganisms than people on Earth |
| Aug 13 | Pop Culture | "Happy Birthday to You" under copyright until a 2016 court settlement |
| Aug 13 | Local (Cincinnati) | Cincinnati chili "ways" from Macedonian brothers Tom & John Kiradjieff, Empress Chili 1922 |
| Aug 17 | History | Cleopatra lived closer to the Moon landing than to the building of the Great Pyramid |
| Aug 17 | Geography | Africa is the only continent in all four hemispheres |
| Aug 17 | Science | Mpemba effect — hot water can freeze faster than cold under some conditions |
| Aug 17 | Food | A pineapple plant takes ~2 years to produce one fruit |
| Aug 17 | Animals | A group of owls is a "parliament" |
| Aug 17 | Space | Jupiter's Great Red Spot shrinking — ~3 Earths wide a century ago, ~1 now |
| Aug 17 | Language | "Nerd" first in print in Dr. Seuss's If I Ran the Zoo (1950) |
| Aug 17 | Sports | Basketball's first hoops (1891) were peach baskets; ball retrieved by ladder after each score |
| Aug 17 | Pop Culture | Sean Connery wore a toupee in every James Bond film |
| Aug 17 | Did You Know | Eiffel Tower had a 20-year permit; saved because it worked as a radio antenna |
| Aug 17 | Body | 2014 study: human nose can distinguish ~1 trillion smells (not 10,000) |
| Aug 17 | Local (Cincinnati) | Music Hall built over a paupers' cemetery/Potter's Field; remains found in the 2016–17 restoration |
| Aug 17 | Reds bar-bet | First MLB night game: May 24, 1935, Crosley Field, Reds 2–1 Phillies; FDR threw the switch from the White House |


---

## 📅 History Dates Covered

| Week | Calendar Date Used for "This Day in History" |
|------|----------------------------------------------|
| Aug 31 | August 31 (Princess Diana dies in Paris crash 1997 — 29th anniv, Pont de l'Alma tunnel; Gdańsk Agreement signed 1980 creating Solidarity; Charleston SC earthquake ~M7.0 1886, 60+ dead; Malaya independence / Merdeka Day 1957) |
| Aug 28 | August 28 (March on Washington / MLK "I Have a Dream" 1963 — 63rd anniv, ~250,000 marchers, Mahalia Jackson's "Tell them about the dream"; first radio commercial on WEAF NYC 1922 — Queensboro Realty, $50 for 10 min; Hurricane Katrina hits Cat 5 and New Orleans issues first-ever mandatory evacuation 2005) |
| Aug 27 | August 27 (Battle of Brooklyn 1776 — 250th anniv; Edwin Drake first US oil well, Titusville PA 1859; Kellogg–Briand Pact signed 1928; Brian Epstein found dead 1967; LBJ born 1908) |
| Aug 26 | August 26 (19th Amendment certified 1920 — Women's Equality Day, 106th anniv; first large-scale hydroelectric plant at Niagara Falls 1895; Jimi Hendrix opens Electric Lady Studios 1970; "Hey Jude" tops UK chart 1968) |
| Aug 25 | August 25 (National Park Service created 1916 — 110th anniv; Matthew Webb first to swim the English Channel 1875; Great Moon Hoax begins in the NY Sun 1835; Liberation of Paris completed 1944; Linus Torvalds announces Linux 1991 — 35th anniv; Neil Armstrong dies 2012) |
| Aug 24 | August 24 (Vesuvius AD 79; British burn Washington 1814; Windows 95 1995; Pluto demoted 2006) |
| Aug 20 | August 20 (8MK Detroit first commercial radio broadcast 1920 → WWJ; NFL organizing meeting in Canton OH with Jim Thorpe 1920; Viking 1 launched 1975; Prague Spring crushed by Soviet invasion 1968; Lou Gehrig's record 23rd career grand slam 1938; Darwin's natural selection first in print, Linnean Society 1858) |
| Aug 19 | August 19 (USS Constitution beats HMS Guerrière 1812 → "Old Ironsides"; Gorbachev put under house arrest in Soviet coup 1991 — 35th anniv; Google IPO on Nasdaq at $85 in 2004; Syncom 3 first geostationary satellite 1964) |


| Jun 18 | June 18 (Battle of Waterloo 1815; War of 1812 declared 1812; Sally Ride first American woman in space 1983) |
| Jun 23 | June 23 (Typewriter patented 1868; IOC founded 1894; Title IX enacted 1972; Tim Burton's Batman released 1989) |
| Aug 13 | August 13 (Berlin Wall goes up 1961 - 65th anniv; Tenochtitlan falls to Cortes 1521 - 505 yrs; pay phone patented by William Gray of Hartford CT 1889; also Florence Nightingale dies 1910, Opha May Johnson first woman US Marine 1918) |


---

## 🎉 National Days Featured

| Week | National Days |
|------|--------------|
| Aug 31 | National Trail Mix Day; National Eat Outside Day; National Matchmaker Day; National South Carolina Day; National Diatomaceous Earth Day; Love Litigating Lawyers Day; Merdeka Day (Malaysia, 1957); National Heroes Day (Philippines) |
| Aug 28 | National Thoughtful Day; Rainbow Bridge Remembrance Day; National Red Wine Day; National Power Rangers Day; National Bow Tie Day; National Cherry Turnover Day |
| Aug 27 | National Just Because Day; National Petroleum Day; National Banana Lovers Day; National Pots de Crème Day; World Rock Paper Scissors Day; Tarzan Day; International Lottery Day; Lyndon Baines Johnson Day (Texas); Moldova Independence Day (1991); Be Kind to Humankind Week |
| Aug 26 | National Dog Day; Women's Equality Day; National Cherry Popsicle Day; National Toilet Paper Day; National Webmistress Day; Make Your Own Luck Day |
| Aug 25 | National Banana Split Day; National Whiskey Sour Day; National Park Service Founders Day; National Kiss and Make Up Day; National Secondhand Wardrobe Day; last day of National Aviation Week; Uruguay Independence Day (1825) |
| Aug 24 | National Waffle Day; National Peach Pie Day; National Knife Day; International Strange Music Day; Kobe Bryant Day |
| Aug 20 | National Radio Day; National Hazy IPA Day (third Thursday in August); National Bacon Lovers Day; National Chocolate Pecan Pie Day; National Accessible Air Travel Day; World Mosquito Day; International Day of Medical Transporters |
| Aug 19 | National Aviation Day (Orville Wright's birthday, set by FDR 1939); World Photography Day; World Humanitarian Day; International Orangutan Day; National Potato Day; National Soft Ice Cream Day; "Black Cow" Root Beer Float Day; National Hot & Spicy Food Day; Afghanistan Independence Day (1919) |


---

---
| Jun 18 | Go Fishing Day; International Picnic Day; National Splurge Day; International Sushi Day; Autistic Pride Day |
| Jun 23 | National Pink Day; National Detroit-Style Pizza Day; National Hydration Day; National Pecan Sandies Day; Pink Flamingo Day; International Widows' Day; UN Public Service Day |
| Jun 24 | World UFO Day; International Fairy Day; National Pralines Day; Celebration of the Senses; Swim a Lap Day; National Parchment Day; St. John's Day (Midsummer) |
| Aug 13 | International Lefthanders Day; National Prosecco Day; National Filet Mignon Day; National Blame Someone Else Day; Central African Republic Independence Day (1960) |
| Aug 17 | National Thrift Shop Day; Black Cat Appreciation Day; National Nonprofit Day; National Massachusetts Day; Balloon Airmail Day; National I Love My Feet Day; Indonesia Independence Day (1945); Gabon Independence Day (1960); Discovery Day (Yukon) |

---

## ⚙️ Founded & Invented Used

| Week | Subject | Key Fact |
|------|---------|---------|

## 🏭 Founded & Invented Used

| Week | Question | Answer |
|------|----------|--------|
| Aug 31 | Twinkie | James Dewar, 1930, Continental Baking IL; original filling banana |
| Aug 31 | Chuck E. Cheese founded | Nolan Bushnell (Atari founder), 1977 |
| Aug 31 | Three-position traffic signal | Garrett Morgan, patented 1923, Cleveland; sold to GE for $40,000 |
| Aug 31 | Toyota founded / name change | 1937, from Toyoda Automatic Loom Works; "t" for 8 katakana strokes |
| Aug 31 | "Super Bowl" name origin | Lamar Hunt, from his kids' Super Ball toy |
| Aug 31 | Rookwood Pottery (Local) | 1880 Cincinnati, Maria Longworth Nichols Storer — woman-owned manufacturer |
| Aug 28 | Harvard founded | 1636 — oldest US university, 140 yrs before the country |
| Aug 28 | Ballpoint pen | László Bíró, Hungarian journalist, patented 1938; "biro" in UK/AUS |
| Aug 28 | Teflon | Roy Plunkett, DuPont, 1938 — accidental polymerization of refrigerant gas |
| Aug 28 | Crayola name origin | Binney & Smith 1903; French *craie* (chalk) + "oleaginous"; first 8-pack a nickel |
| Aug 28 | Sony founded | 1946 Tokyo, Masaru Ibuka & Akio Morita as Tokyo Tsushin Kogyo; renamed 1958 |
| Aug 28 | U.S. Playing Card Co. (Local) | Cincinnati, traces to 1867; Bicycle brand 1885; Norwood plant until 2009 |
| Aug 27 | Ford Motor Company founded | 1903, Detroit; Henry Ford + 11 investors, ~$28,000 |
| Aug 27 | Frisbee | Walter Frederick Morrison's "Pluto Platter"; sold to Wham-O 1957 |
| Aug 27 | First barcode scan | June 1974, Wrigley's gum, Marsh supermarket, Troy OH; patent Woodland & Silver 1952 |
| Aug 27 | Implantable pacemaker | Wilson Greatbatch, 1958 — wrong-sized resistor accident |
| Aug 27 | IKEA founded | 1943, Ingvar Kamprad age 17; name = initials + Elmtaryd + Agunnaryd |
| Aug 27 | Ivory Soap (Local) | P&G 1879; Harley Procter named it from Psalm 45:8; "99 44/100% pure" |
| Aug 26 | Slinky | Richard James, 1943 Navy engineer; ship stabilizer spring; Gimbels 1945 |
| Aug 26 | Amazon founded | 1994, Jeff Bezos, Bellevue WA garage; first name choice "Cadabra" |
| Aug 26 | WD-40 name | "Water Displacement, 40th formula" — Rocket Chemical Co., 1953 |
| Aug 26 | Super Soaker | Lonnie Johnson, NASA/JPL engineer, 1982 heat-pump accident; launched 1990 |
| Aug 26 | Band-Aid | Earle Dickson, J&J, 1920, for his accident-prone wife |
| Aug 26 | Skyline Chili (Local) | 1949, Nicholas Lambrinides, Price Hill; named for the Cincinnati skyline view |
| Aug 25 | LEGO founded | 1932, Billund Denmark, Ole Kirk Christiansen; name from 'leg godt'; brick 1958 |
| Aug 25 | Post-it Note | Spencer Silver (weak adhesive 1968) + Art Fry (1974), 3M; launched 1980 |
| Aug 25 | Chocolate chip cookie | Ruth Wakefield, Toll House Inn MA, 1938; sold recipe to Nestlé |
| Aug 25 | ATM | John Shepherd-Barron, Barclays Enfield London, 1967; 4-digit PIN due to his wife |
| Aug 25 | Nike original name | Blue Ribbon Sports (1964); renamed Nike 1971; swoosh by Carolyn Davidson, $35 |
| Aug 25 | Graeter's (Local) | 1870 Cincinnati, Louis Charles Graeter — French pot method, 2 gal at a time |
| Aug 24 | Google founded | 1998, Larry Page & Sergey Brin, Menlo Park garage (orig. "BackRub") |
| Aug 24 | Rubik's Cube | Ernő Rubik, 1974 |
| Aug 24 | Dr Pepper | 1885, Waco TX — oldest major US soft drink |
| Aug 24 | Hershey Chocolate Company | Milton Hershey, 1894 |
| Aug 24 | FedEx | Fred Smith, 1971 |
| Aug 24 | Etch A Sketch | André Cassagnes; Ohio Art, 1960 |
| Aug 20 | Bubble wrap original purpose | Textured wallpaper — Fielding & Chavannes, 1957 (two sealed shower curtains) |
| Aug 20 | Play-Doh original purpose (Local) | Wallpaper cleaner — Kutol Products, Cincinnati; repurposed as a toy mid-1950s |
| Aug 20 | Coca-Cola inventor / year | John Pemberton, Atlanta pharmacist, 1886 (name & logo by bookkeeper Frank Robinson) |
| Aug 20 | Microsoft founded where/when | Albuquerque, New Mexico, 1975 (near MITS/Altair 8800) |
| Aug 20 | Three-point seat belt | Nils Bohlin, Volvo, 1959 — Volvo released the patent for free |
| Aug 20 | First Jacuzzi whirlpool pump | Candido Jacuzzi, 1956, for his son's rheumatoid arthritis |
| Aug 19 | Microwave oven inventor | Percy Spencer (Raytheon, 1945) — chocolate bar melted near a magnetron |
| Aug 19 | Riveted blue jeans patent | 1873 — Levi Strauss with tailor Jacob Davis of Reno |
| Aug 19 | Nintendo founded / original product | 1889, Kyoto — hanafuda playing cards |
| Aug 19 | Velcro inventor / inspiration | George de Mestral — burdock burrs on his dog, 1941; patented 1955 |
| Aug 19 | Harley-Davidson founded | 1903, Milwaukee (William Harley + Davidson brothers) |
| Aug 19 | Kroger founded (Local) | Barney Kroger, Cincinnati, 1883, with $372 of savings |


| Jun 18 | Who invented dynamite (1867)? | Alfred Nobel |
| Jun 18 | Toyota Motor Corporation founded year | 1937 (Kiichiro Toyoda) |
| Jun 18 | Inventor of electronic television (1927) | Philo Farnsworth |
| Jun 18 | Inventor of movable-type printing press (c.1440) | Johannes Gutenberg |
| Jun 18 | Designer of original Ferris Wheel (1893 Chicago) | George W. Ferris |
| Jun 18 | Inventor of the safety pin (1849) | Walter Hunt |
| Jun 23 | Penicillin discovered (1928) | Alexander Fleming |
| Jun 23 | Vaseline / petroleum jelly (1872) | Robert Chesebrough |
| Jun 23 | Practical light bulb (1879) | Thomas Edison |
| Jun 23 | Ferrari founded | Enzo Ferrari (1939; first car 1947) |
| Jun 23 | IBM founded year | 1911 (as CTR; renamed IBM 1924) |
| Jun 23 | Bagless cyclone vacuum (1991) | James Dyson (5,127 prototypes) |
| Jun 24 | First gasoline automobile patent (1886) | Karl Benz |
| Jun 24 | Safety razor inventor | King C. Gillette (1901; sold 1903) |
| Jun 24 | KFC founder | Colonel Harland Sanders (first franchise 1952) |
| Jun 24 | First powered airplane flight (1903) | Wright Brothers |
| Jun 24 | Lamborghini founded (1963) | Ferruccio Lamborghini |
| Jun 24 | Lockstitch sewing machine patent (1846) | Elias Howe |
| Aug 13 | Barbie creator/year | Ruth Handler, Mattel, 1959 (named for daughter Barbara) |
| Aug 13 | Monopoly - patent vs true origin | Charles Darrow patented 1935; from Lizzie Magie's 1904 "The Landlord's Game" |
| Aug 13 | Corn flakes inventors | Kellogg brothers, Battle Creek MI, 1894 accident; company 1906 |
| Aug 13 | Dishwasher inventor | Josephine Cochrane, 1886 |
| Aug 13 | Duct tape origin | 1943, Vesta Stoudt's idea, made by Johnson & Johnson; called "duck tape" |
| Aug 13 | Procter & Gamble founded | 1837 Cincinnati; William Procter (candles) & James Gamble (soap), brothers-in-law |


---

## 🎵 Music Used (1990–2010)

| Week | Song | Artist | Year |
|------|------|--------|------|
| Aug 31 | Losing My Religion | R.E.M. | 1991 |
| Aug 31 | No Rain | Blind Melon | 1992 |
| Aug 31 | 1979 | The Smashing Pumpkins | 1995 |
| Aug 31 | Doo Wop (That Thing) | Lauryn Hill | 1998 |
| Aug 31 | The Middle | Jimmy Eat World | 2001 |
| Aug 31 | Crazy in Love | Beyoncé feat. JAY-Z | 2003 |
| Aug 28 | Basket Case | Green Day | 1994 |
| Aug 28 | Interstate Love Song | Stone Temple Pilots | 1994 |
| Aug 28 | California Love | 2Pac feat. Dr. Dre & Roger Troutman | 1995 |
| Aug 28 | Semi-Charmed Life | Third Eye Blind | 1997 |
| Aug 28 | Clocks | Coldplay | 2002 |
| Aug 28 | Float On | Modest Mouse | 2004 |
| Aug 27 | Regulate | Warren G feat. Nate Dogg |
| Aug 27 | Everlong | Foo Fighters |
| Aug 27 | Torn | Natalie Imbruglia |
| Aug 27 | How You Remind Me | Nickelback |
| Aug 27 | Hot in Herre | Nelly |
| Aug 27 | Chasing Cars | Snow Patrol |
| Aug 26 | Loser | Beck | 1994 |
| Aug 26 | Waterfalls | TLC | 1995 |
| Aug 26 | Bitter Sweet Symphony | The Verve | 1997 |
| Aug 26 | Seven Nation Army | The White Stripes | 2003 |
| Aug 26 | Mr. Brightside | The Killers | 2004 |
| Aug 26 | Rehab | Amy Winehouse | 2006 |
| Aug 25 | Vogue | Madonna | 1990 |
| Aug 25 | Black Hole Sun | Soundgarden | 1994 |
| Aug 25 | Wonderwall | Oasis | 1995 |
| Aug 25 | Santeria | Sublime | 1996 |
| Aug 25 | Since U Been Gone | Kelly Clarkson | 2004 |
| Aug 25 | Crazy | Gnarls Barkley | 2006 |
| Aug 24 | Just a Girl | No Doubt | 1995 |
| Aug 24 | Cumbersome | Seven Mary Three | 1995 |
| Aug 24 | Killing Me Softly With His Song | Fugees | 1996 |
| Aug 24 | Otherside | Red Hot Chili Peppers | 1999 |
| Aug 24 | Ms. Jackson | OutKast | 2000 |
| Aug 24 | Bad Romance | Lady Gaga | 2009 |
| Aug 20 | Linger | The Cranberries | 1993 |
| Aug 20 | Gin and Juice | Snoop Doggy Dogg | 1993 |
| Aug 20 | One Week | Barenaked Ladies | 1998 |
| Aug 20 | Last Resort | Papa Roach | 2000 |
| Aug 20 | Maps | Yeah Yeah Yeahs | 2003 |
| Aug 20 | Paper Planes | M.I.A. | 2007 |
| Aug 19 | Come As You Are | Nirvana | 1991 |
| Aug 19 | Sabotage | Beastie Boys | 1994 |
| Aug 19 | No Diggity | Blackstreet feat. Dr. Dre & Queen Pen | 1996 |
| Aug 19 | Karma Police | Radiohead | 1997 |
| Aug 19 | Last Nite | The Strokes | 2001 |
| Aug 19 | Feel Good Inc. | Gorillaz feat. De La Soul | 2005 |

---

---







































































































































































| Jun 18 | Bring Me to Life | Evanescence | 2003 |
| Jun 18 | Hey Jealousy | Gin Blossoms | 1992 |
| Jun 18 | Semi-Charmed Life | Third Eye Blind | 1997 |
| Jun 18 | Stay (I Missed You) | Lisa Loeb & Nine Stories | 1994 |
| Jun 18 | Sex and Candy | Marcy Playground | 1997 |
| Jun 18 | You Oughta Know | Alanis Morissette | 1995 |
| Aug 13 | Jeremy | Pearl Jam | 1991 |
| Aug 13 | Self Esteem | The Offspring | 1994 |
| Aug 13 | Ironic | Alanis Morissette | 1996 |
| Aug 13 | Hanging by a Moment | Lifehouse | 2001 |
| Aug 13 | In da Club | 50 Cent | 2003 |
| Aug 13 | Kids | MGMT | 2008 |


## June 9, 2026 (v22)

### Capitals
| Jun 9 | Luxembourg | Luxembourg City |
| Jun 9 | Philippines | Manila |
| Jun 9 | Jordan | Amman |
| Jun 9 | Cameroon | Yaoundé |

### Classic TV
| Jun 9 | Monk (2002–09) | Adrian Monk | Tony Shalhoub |
| Jun 9 | The Wire (2002–08) | Det. Jimmy McNulty | Dominic West |
| Jun 9 | Marcus Welby, M.D. (1969–76) | Dr. Marcus Welby | Robert Young |
| Jun 9 | Barnaby Jones (1973–80) | Barnaby Jones | Buddy Ebsen |
| Jun 9 | Charmed (1998–2006) | Piper Halliwell | Holly Marie Combs |
| Jun 9 | The Larry Sanders Show (1992–98) | Larry Sanders | Garry Shandling |

### Arts & Literature
| Jun 9 | Middlemarch (1871) author | George Eliot (Mary Ann Evans) |
| Jun 9 | The Thinker sculptor | Auguste Rodin |
| Jun 9 | Norwegian Wood (1987) author | Haruki Murakami |
| Jun 9 | Washington Crossing the Delaware painter | Emanuel Leutze |
| Jun 9 | Midnight's Children (1981) author | Salman Rushdie |
| Jun 9 | The Kite Runner (2003) author | Khaled Hosseini |

### Founded & Invented
| Jun 9 | Safety razor patent (1901) | King Camp Gillette |
| Jun 9 | Phonograph invented (1877) | Thomas Edison |
| Jun 9 | First commercial airline flight (Jan 1, 1914) | St. Petersburg to Tampa, FL; pilot Tony Jannus; $5 fare |
| Jun 9 | Wrigley Company (1891) | William Wrigley Jr.; originally sold baking powder; gum was the bonus |
| Jun 9 | Colgate (1806) | William Colgate; originally soap, starch, and candles |
| Jun 9 | Ziploc bag (1968) | Dow Chemical |

### General Trivia
| Jun 9 | Animals | Wolverines ("skunk bears") drive bears/mountain lions from carcasses |
| Jun 9 | History | Roman Empire peak ~117 AD = ~70M people = ~20% of world population |
| Jun 9 | Science | Electric eel is not an eel — it's a knifefish; generates up to 860 volts |
| Jun 9 | Mandela Effect | Monopoly man (Rich Uncle Pennybags) never had a monocle |
| Jun 9 | Science | Water expands ~9% when freezing — why ice floats, pipes burst |
| Jun 9 | Geography | Tokyo metro (~37.4M) larger than entire population of Canada (~38M) |
| Jun 9 | History | Cleopatra spoke 9 languages; first Ptolemaic ruler to learn Egyptian |
| Jun 9 | Animals | Blue whale heart beats 2–6 times/min when diving deep |
| Jun 9 | Food | Nutmeg (myristicin) causes hallucinations/toxicity in large doses |
| Jun 9 | Biology | Human eye distinguishes ~10 million different colors |

### Songs
| Jun 9 | November Rain | Guns N' Roses | 1991 |
| Jun 9 | Santeria | Sublime | 1996 |
| Jun 9 | Teardrop | Massive Attack | 1998 |
| Jun 9 | Beautiful | Christina Aguilera | 2002 |
| Jun 9 | Take Me Out | Franz Ferdinand | 2004 |
| Jun 9 | Chasing Cars | Snow Patrol | 2006 |

### This Day in History
| Jun 9 | June 9 (Kingsford Smith trans-Pacific 1928; Donald Duck debut 1934; Golan Heights captured 1967; Thatcher reelected 1983; Griffey 600th HR 2010) | — |
| Jun 9 | National Days: National Donald Duck Day; National Food Truck Day; National Strawberry-Rhubarb Pie Day; International Dark 'n Stormy Day; World Tessellation Day | — |

### Sports / Current Events
| Jun 9 | Sports | NBA Finals: Knicks lead Spurs 2-1; G3 Spurs 115-111 MSG; Wembanyama 32/8/6; G4 Tue Jun 10 SA |
| Jun 9 | Sports | NHL SCF: Golden Knights lead Hurricanes 2-1; G3 VGK 5-4 2OT; Marner fastest hat trick in Finals history (28 pts series); G4 tonight LV |
| Jun 9 | Sports | FIFA World Cup 2026 opens June 11; Mexico vs South Africa at Azteca; first 48-team / 3-nation WC |
| Jun 9 | Sports | MLB: Misiorowski (Brewers) 103.7 mph — MLB record for a starting pitcher |
| Jun 9 | Sports | Reds 31-33 .484 NL Central 5th 9.5 GB; L4 streak; @ SD Padres 9:40 PM ET |
| Jun 9 | Box Office | Scary Movie #1 ~$55M domestic / ~$105.5M global; Masters of Universe #2 ~$31M |
| Jun 9 | Deaths | Anthony Head (72, Giles/Buffy, June 1); Peabo Bryson (75, R&B, June 2); Marjane Satrapi (56, Persepolis, June 4); Alan Hale (68, comet Hale-Bopp, June 6) |


## June 10, 2026 (v23)

### Capitals
| Jun 10 | Fiji | Suva |
| Jun 10 | Costa Rica | San José |
| Jun 10 | Uzbekistan | Tashkent |
| Jun 10 | Rwanda | Kigali |

### Classic TV
| Jun 10 | Gomer Pyle, U.S.M.C. (1964–69) | Gomer Pyle | Jim Nabors |
| Jun 10 | Daniel Boone (1964–70) | Daniel Boone | Fess Parker |
| Jun 10 | The Virginian (1962–71) | The Virginian | James Drury |
| Jun 10 | Combat! (1962–67) | Sgt. Chip Saunders | Vic Morrow |
| Jun 10 | Evening Shade (1990–94) | Wood Newton | Burt Reynolds |
| Jun 10 | Crime Story (1986–88) | Lt. Mike Torello | Dennis Farina |

### Arts & Literature
| Jun 10 | The Call of the Wild / White Fang author | Jack London |
| Jun 10 | Treasure Island author | Robert Louis Stevenson |
| Jun 10 | "Surprise Symphony" / Father of the Symphony | Joseph Haydn |
| Jun 10 | "I Wandered Lonely as a Cloud" (daffodils) poet | William Wordsworth |
| Jun 10 | Around the World in Eighty Days author | Jules Verne |
| Jun 10 | "View of Toledo" / elongated figures painter | El Greco |

### Founded & Invented
| Jun 10 | Oreo cookie debut (1912) | Nabisco |
| Jun 10 | Automatic dishwasher (1886) | Josephine Cochrane |
| Jun 10 | Dell (1984) | Michael Dell; started in his UT Austin dorm room |
| Jun 10 | Intel (1968) | Gordon Moore & Robert Noyce |
| Jun 10 | Sliced bread / bread-slicing machine (1928) | Otto Rohwedder |
| Jun 10 | Toblerone (1908) | Swiss; hidden bear in the Matterhorn logo |

### General Trivia
| Jun 10 | Animals | Cows have regional "accents" in their moos |
| Jun 10 | Did You Know | Vending machines cause more deaths/year on average than sharks |
| Jun 10 | Pop Culture | Twitter's bird logo was named "Larry," after Larry Bird |
| Jun 10 | Animals | Crocodiles cannot stick out their tongues |
| Jun 10 | Food | Pound cake = a pound each of butter, sugar, flour, eggs |
| Jun 10 | Geography | Point Nemo: ocean's most remote spot; nearest humans often on the ISS |
| Jun 10 | Geography | Mt. Chimborazo (Ecuador), not Everest, is farthest from Earth's center |
| Jun 10 | Science | Tungsten has the highest melting point of any metal (~6,192°F) |
| Jun 10 | Biology | Axolotls regrow limbs, heart parts, even portions of their brain |
| Jun 10 | Language | Fear of Friday the 13th = paraskevidekatriaphobia |

### Songs
| Jun 10 | Mr. Brightside | The Killers | 2004 |
| Jun 10 | Zombie | The Cranberries | 1994 |
| Jun 10 | Iris | Goo Goo Dolls | 1998 |
| Jun 10 | Seven Nation Army | The White Stripes | 2003 |
| Jun 10 | Hey Ya! | OutKast | 2003 |
| Jun 10 | Crazy | Gnarls Barkley | 2006 |

### This Day in History
| Jun 10 | June 10 (Alcoholics Anonymous founded 1935; Six-Day War ceasefire 1967; The Sopranos finale 2007) | — |
| Jun 10 | National Days: National Iced Tea Day; National Ballpoint Pen Day; National Egg Roll Day; National Black Cow Day | — |

### Sports / Current Events
| Jun 10 | Sports | NBA Finals: Knicks lead Spurs 2-1; G3 Spurs 115-111 MSG; G4 tonight Jun 10 MSG 8:30 ET |
| Jun 10 | Sports | NHL SCF: Hurricanes-Golden Knights tied 2-2; G4 CAR 5-3 (Staal 2G); G5 Thu Jun 11 Carolina |
| Jun 10 | Sports | FIFA World Cup opens Jun 11, Mexico vs South Africa at Azteca; Shakira opening ceremony |
| Jun 10 | Sports | NFL minicamps: AJ Brown PHI->NE; Myles Garrett CLE->LAR; Mahomes record extension thru 2033 |
| Jun 10 | Sports | NCAA: CWS field set, 8 teams to Omaha (record 5 SEC); starts Fri Jun 12 |
| Jun 10 | Sports | Tennis: Zverev wins 1st major at French Open (def Cobolli); Mirra Andreeva wins women's |
| Jun 10 | Sports | Reds 32-34 5th NL Central 9.5 GB; snapped 5-game skid (Stewart 11th-inn HR 5-3); @ SD 4:10 ET |
| Jun 10 | Box Office | Scary Movie #1 $55M domestic / $105.5M global; Toy Story 5 (Jun 19) & Supergirl (Jun 26) upcoming |
| Jun 10 | Deaths | Gordon S. Wood (92, historian); Talay Riley (35, singer); Sally Grace (74, actress); Sir John Swan (90, Bermuda premier) |

## June 11, 2026 (v24)

### Capitals
| Jun 11 | Panama | Panama City |
| Jun 11 | Zambia | Lusaka |
| Jun 11 | Syria | Damascus |
| Jun 11 | Belarus | Minsk |

### Classic TV
| Jun 11 | Batman (1966–68) | Bruce Wayne / Batman | Adam West |
| Jun 11 | The Patty Duke Show (1963–66) | Patty & Cathy Lane | Patty Duke |
| Jun 11 | Hazel (1961–66) | Hazel Burke | Shirley Booth |
| Jun 11 | Martin (1992–97) | Martin Payne | Martin Lawrence |
| Jun 11 | Star Trek: Deep Space Nine (1993–99) | Capt. Benjamin Sisko | Avery Brooks |
| Jun 11 | JAG (1995–2005) | Harmon "Harm" Rabb Jr. | David James Elliott |

### Arts & Literature
| Jun 11 | The Chronicles of Narnia author | C.S. Lewis |
| Jun 11 | "Ode on a Grecian Urn" poet | John Keats |
| Jun 11 | "Luncheon of the Boating Party" painter | Pierre-Auguste Renoir |
| Jun 11 | "Wedding March" (A Midsummer Night's Dream) composer | Felix Mendelssohn |
| Jun 11 | The Cherry Orchard / The Seagull playwright | Anton Chekhov |
| Jun 11 | "Ozymandias" poet | Percy Bysshe Shelley |

### Founded & Invented
| Jun 11 | Chevrolet (1911) | Louis Chevrolet & William Durant |
| Jun 11 | Steel plow (1837) | John Deere |
| Jun 11 | Elevator safety brake (1853) | Elisha Otis |
| Jun 11 | Three-position traffic signal (1923) | Garrett Morgan |
| Jun 11 | First ATM / cash machine (1967, London) | John Shepherd-Barron |
| Jun 11 | Rolex (1905) | Hans Wilsdorf |

### General Trivia
| Jun 11 | Animals | Slugs have four noses |
| Jun 11 | Language | "Dreamt" is the only common English word ending in "mt" |
| Jun 11 | Did You Know | The Statue of Liberty wears a size 879 sandal |
| Jun 11 | Language | The toothpaste blob on a brush is called a "nurdle" |
| Jun 11 | Animals | A flock of swooping starlings is a "murmuration" |
| Jun 11 | Science | Apple seeds contain amygdalin (releases trace cyanide when crushed) |
| Jun 11 | Animals | Lobsters taste with their legs, smell with their antennae |
| Jun 11 | Animals | Immortal jellyfish (Turritopsis dohrnii) can revert to an earlier life stage |
| Jun 11 | History | "Baker's dozen" = 13; extra loaf to avoid penalties for short weight |
| Jun 11 | Animals | Sea cucumbers expel their organs to defend themselves, then regrow them |
| Jun 11 | Animals | Cats have a third eyelid (nictitating membrane) |
| Jun 11 | Language | "Brunch" is a portmanteau first seen in an 1895 British magazine |

### Songs
| Jun 11 | Smells Like Teen Spirit | Nirvana | 1991 |
| Jun 11 | Losing My Religion | R.E.M. | 1991 |
| Jun 11 | Wonderwall | Oasis | 1995 |
| Jun 11 | No Scrubs | TLC | 1999 |
| Jun 11 | Smooth | Santana feat. Rob Thomas | 1999 |
| Jun 11 | Yellow | Coldplay | 2000 |

### This Day in History
| Jun 11 | June 11 (Committee of Five named 1776; Wallace "schoolhouse door" / U. Alabama desegregated 1963; E.T. opens 1982) | — |
| Jun 11 | National Days: National Corn on the Cob Day; National German Chocolate Cake Day; King Kamehameha Day (HI); Yarn Bombing Day | — |

### Sports / Current Events
| Jun 11 | Sports | FIFA World Cup opens today Jun 11 (US/Mexico/Canada co-host); Mexico opener at Estadio Azteca |
| Jun 11 | Sports | NBA Finals: Knicks lead Spurs 3-1; G4 NYK 107-106 (29-pt comeback); G5 Sat Jun 13 San Antonio |
| Jun 11 | Sports | NHL SCF: Golden Knights-Hurricanes tied 2-2; G4 CAR 5-3 (Staal 2G); G5 back in Carolina |
| Jun 11 | Sports | NCAA: Men's CWS opens Fri Jun 12 Omaha; WVU-Troy & UNC-Ole Miss Day 1 (5 SEC teams) |
| Jun 11 | Sports | NFL minicamps wrapping; Browns Sanders-Watson QB battle; camps break to late July |
| Jun 11 | Sports | Reds 32-35 5th NL Central 9.5 GB / WC 3.0 back; lost SD finale 5-4; OFF today (home weekend next) |
| Jun 11 | Box Office | Scary Movie #1 $55M domestic (franchise best) / $105.5M global, $30M budget; Wayans back after 25 yrs |
| Jun 11 | Deaths | Anthony Head (72, Buffy/Ted Lasso); Marjane Satrapi (56, Persepolis); Ned Jarrett (93, NASCAR); James Handy (81, actor) |

## June 12, 2026 (v25)

### Capitals
| Jun 12 | India | New Delhi |
| Jun 12 | Angola | Luanda |
| Jun 12 | Honduras | Tegucigalpa |
| Jun 12 | Turkmenistan | Ashgabat |

### Classic TV
| Jun 12 | Gidget (1965–66) | Gidget (Frances Lawrence) | Sally Field |
| Jun 12 | That Girl (1966–71) | Ann Marie | Marlo Thomas |
| Jun 12 | The Monkees (1966–68) | Davy (himself) | Davy Jones |
| Jun 12 | Space: 1999 (1975–77) | Cdr. John Koenig | Martin Landau |
| Jun 12 | Fantasy Island (1977–84) | Mr. Roarke | Ricardo Montalbán |
| Jun 12 | One Day at a Time (1975–84) | Ann Romano | Bonnie Franklin |

### Arts & Literature
| Jun 12 | First American Nobel Literature laureate (1930); Babbitt / Main Street | Sinclair Lewis |
| Jun 12 | "Judith Slaying Holofernes" Baroque painter | Artemisia Gentileschi |
| Jun 12 | "The Entertainer" ragtime composer | Scott Joplin |
| Jun 12 | First African American to win a Pulitzer (1950, Annie Allen) | Gwendolyn Brooks |
| Jun 12 | "A Good Man Is Hard to Find" author | Flannery O'Connor |
| Jun 12 | All the King's Men author | Robert Penn Warren |

### Founded & Invented
| Jun 12 | Chipotle (1993) | Steve Ells (Denver) |
| Jun 12 | Implantable cardiac pacemaker | Wilson Greatbatch |
| Jun 12 | Spanx (2000) | Sara Blakely |
| Jun 12 | QR code (1994) | Denso Wave / Masahiro Hara |
| Jun 12 | First network email & "@" address (1971) | Ray Tomlinson |
| Jun 12 | Trader Joe's (1967) | Joe Coulombe |

### General Trivia
| Jun 12 | Music | Spain & Bosnia national anthems have no official lyrics |
| Jun 12 | Law/Animals | Switzerland: owning a single guinea pig can be illegal (social animals need pairs) |
| Jun 12 | Nature | Total biomass of all ants ≈ total biomass of all humans |
| Jun 12 | Sports | Tennis balls were white until 1972; switched to "optic yellow" for color TV |
| Jun 12 | Biology | Some turtles breathe through their cloaca (rear) while hibernating underwater |
| Jun 12 | Nature | Largest living organism is a honey fungus in Oregon (~3.7 sq mi) |
| Jun 12 | Science | "Brain freeze" = sphenopalatine ganglioneuralgia |
| Jun 12 | Anatomy | The "funny bone" is the ulnar nerve, not a bone |
| Jun 12 | Etymology | The "$" sign likely evolved from the Spanish peso abbreviation |
| Jun 12 | Language | "Strengths" is among the longest words with a single vowel |
| Jun 12 | Environment | Recycling one aluminum can = ~3 hours of TV power |
| Jun 12 | Science | More atoms in a glass of water than glasses of water in all the oceans |

### Songs
| Jun 12 | Glycerine | Bush | 1994 |
| Jun 12 | One Headlight | The Wallflowers | 1996 |
| Jun 12 | Slide | Goo Goo Dolls | 1998 |
| Jun 12 | Drive | Incubus | 2001 |
| Jun 12 | How to Save a Life | The Fray | 2005 |
| Jun 12 | Feel Good Inc. | Gorillaz | 2005 |

### This Day in History
| Jun 12 | June 12 (Baseball Hall of Fame opens Cooperstown 1939; Medgar Evers assassinated 1963; Reagan "tear down this wall" 1987) | — |
| Jun 12 | National Days: Loving Day (Loving v. Virginia 1967); Red Rose Day; Peanut Butter Cookie Day; National Jerky Day; International Falafel Day | — |

### Sports / Current Events
| Jun 12 | Sports | FIFA World Cup underway (48 teams; US/MEX/CAN): Mexico 2-0 South Africa (3 reds), Korea 2-1 Czechia; USMNT opens vs Paraguay tonight |
| Jun 12 | Sports | NBA Finals: Knicks lead Spurs 3-1 (G4 29-pt comeback, Anunoby tip-in); G5 Sat Jun 13 San Antonio |
| Jun 12 | Sports | NHL SCF: Hurricanes lead Golden Knights 3-2 (G5 CAR 4-2); can clinch G6 Sun in Las Vegas |
| Jun 12 | Sports | MLB: Braves best record; Ohtani early Cy Young form; Yankees' Aaron Judge out with rib injury |
| Jun 12 | Sports | Reds 32-35 5th NL Central 9.5 GB / WC 3.0 back; 1-6 last 7; host Arizona today 7:15 ET (Lodolo vs E. Rodriguez) |
| Jun 12 | Box Office | Scary Movie #1 $55M domestic / $105.5M global, $30M budget; Wayans return after 25 yrs |
| Jun 12 | Deaths | Peabo Bryson (75, R&B singer); Rick Adelman (79, NBA coach); Anthony Head (72, Buffy/Ted Lasso); Bill Cody (67, radio DJ) |


## June 17, 2026 (v26)

### Capitals
| Jun 17 | Jamaica | Kingston |
| Jun 17 | Vanuatu | Port Vila |
| Jun 17 | Yemen | Sana'a |
| Jun 17 | Brunei | Bandar Seri Begawan |

### Classic TV
| Jun 17 | The Phil Silvers Show (1955-59) | Sgt. Ernie Bilko | Phil Silvers |
| Jun 17 | Wanted: Dead or Alive (1958-61) | Josh Randall | Steve McQueen |
| Jun 17 | Car 54, Where Are You? (1961-63) | Officer Gunther Toody | Joe E. Ross |
| Jun 17 | What's Happening!! (1976-79) | Roger "Raj" Thomas | Ernest Thomas |
| Jun 17 | Vega$ (1978-81) | Dan Tanna | Robert Urich |
| Jun 17 | Bosom Buddies (1980-82) | Kip "Buffy" Wilson | Tom Hanks |

### Arts & Literature
| Jun 17 | One Hundred Years of Solitude author | Gabriel García Márquez |
| Jun 17 | Mrs Dalloway / To the Lighthouse author | Virginia Woolf |
| Jun 17 | "Ride of the Valkyries" / Ring cycle composer | Richard Wagner |
| Jun 17 | The Great Wave off Kanagawa artist | Katsushika Hokusai |
| Jun 17 | Don Quixote author | Miguel de Cervantes |
| Jun 17 | The Metamorphosis (Gregor Samsa) author | Franz Kafka |

### Founded & Invented
| Jun 17 | Potato chip (1853, Saratoga Springs) | George Crum |
| Jun 17 | Corn Flakes (1894, accidental) | Kellogg brothers |
| Jun 17 | Cash register / "Incorruptible Cashier" (1879) | James Ritty |
| Jun 17 | Escalator / inclined elevator (1896, Coney Island) | Jesse Reno |
| Jun 17 | Gore-Tex (1969, stretched PTFE) | Bob Gore |
| Jun 17 | Segway (2001) | Dean Kamen |

### General Trivia
| Jun 17 | Food | Honey never spoils — 3,000-yr-old edible honey found in Egyptian tombs |
| Jun 17 | Botany | Bananas are berries; strawberries are not |
| Jun 17 | Animals | Octopuses have three hearts and blue (copper-based) blood |
| Jun 17 | Nature | Sharks (~450M yrs) are older than trees (~390M yrs) |
| Jun 17 | Science | A lightning bolt is ~5x hotter than the Sun's surface |
| Jun 17 | History | Shortest war ever: Anglo-Zanzibar War (1896), ~38 minutes |
| Jun 17 | Astronomy | Venus rotates opposite most planets; Sun rises in the west there |
| Jun 17 | Language | A group of flamingos is a "flamboyance" |
| Jun 17 | Geography | Scotland's national animal is the unicorn |
| Jun 17 | Did You Know | Pringles designer Fredric Baur had ashes buried in a Pringles can |
| Jun 17 | Science | Mpemba effect — hot water can freeze faster than cold |
| Jun 17 | Math | More possible chess games than atoms in the observable universe |

### Songs
| Jun 17 | Today | The Smashing Pumpkins | 1993 |
| Jun 17 | Closing Time | Semisonic | 1998 |
| Jun 17 | Last Nite | The Strokes | 2001 |
| Jun 17 | The Middle | Jimmy Eat World | 2001 |
| Jun 17 | Maps | Yeah Yeah Yeahs | 2003 |
| Jun 17 | Are You Gonna Be My Girl | Jet | 2003 |

### This Day in History
| Jun 17 | June 17 (Battle of Bunker Hill 1775; Statue of Liberty arrives NYC in 214 crates 1885; Watergate break-in 1972; O.J. Bronco chase 1994) | — |
| Jun 17 | National Days: Eat Your Vegetables Day; National Root Beer Day; National Apple Strudel Day; National Cherry Tart Day; Global Garbage Man Day; Bunker Hill Day | — |

### Sports / Current Events
| Jun 17 | Sports | NBA CHAMPIONS: Knicks beat Spurs 4-1 (G5 94-90 in SA); Brunson Finals MVP (45 in clincher); first NY title since 1973 |
| Jun 17 | Sports | NHL: Hurricanes win Stanley Cup, beat Vegas 4-2 (G6 3-0 shutout Jun 14); Jordan Staal (37) Conn Smythe, oldest ever |
| Jun 17 | Sports | FIFA World Cup group stage: USMNT won opener 4-1, next vs Australia Jun 19 Seattle; Cape Verde drew Spain, Saudi drew Uruguay |
| Jun 17 | Sports | MLB: Brewers 44-26 best record / lead NL Central; Reds 35-37 5th, 10 GB, 3 GB WC; won 2 straight vs Mets (12-0, 5-3) |
| Jun 17 | Reds | 35-37 5th NL Central 10.0 GB / WC 3.0 back; L-W-L-W-W last 5 (W2); vs NY Mets today 12:40 PM ET (Lodolo vs McLean) |
| Jun 17 | Box Office | Disclosure Day (Spielberg sci-fi) #1, $44M open / 3,824 theaters / $115M budget; cast Blunt, O'Connor, Firth, Domingo |
| Jun 17 | Deaths | Gene Shalit (99, Today show film critic, Jun 12); Oliver Tree (32, singer/performance artist, helicopter accident Jun 14) |
| Jun 17 | News | Trump announces Iran peace deal (reopen Strait of Hormuz) at G7 France; B-52 crash; Sudan 1,000+ drone deaths; Congo Ebola outbreak |


## June 18, 2026 (v27)

### Capitals
| Jun 18 | Nevada | Carson City |
| Jun 18 | Missouri | Jefferson City |
| Jun 18 | Greece | Athens |
| Jun 18 | Kenya | Nairobi |

### Classic TV
| Jun 18 | The Rifleman (1958–63) | Lucas McCain | Chuck Connors |
| Jun 18 | Maverick (1957–62) | Bret Maverick | James Garner |
| Jun 18 | Maude (1972–78) | Maude Findlay | Bea Arthur |
| Jun 18 | The Love Boat (1977–86) | Capt. Merrill Stubing | Gavin MacLeod |
| Jun 18 | Falcon Crest (1981–90) | Angela Channing | Jane Wyman |
| Jun 18 | Benson (1979–86) | Benson DuBois | Robert Guillaume |

### Arts & Literature
| Jun 18 | Dracula (1897) author | Bram Stoker |
| Jun 18 | Little Women author | Louisa May Alcott |
| Jun 18 | "Clair de Lune" composer | Claude Debussy |
| Jun 18 | Gulliver's Travels (1726) author | Jonathan Swift |
| Jun 18 | The Little Mermaid / Ugly Duckling author | Hans Christian Andersen |
| Jun 18 | Fahrenheit 451 author | Ray Bradbury |

### Founded & Invented
| Jun 18 | Dynamite (1867) | Alfred Nobel |
| Jun 18 | Toyota Motor Corporation (1937) | Kiichiro Toyoda |
| Jun 18 | Electronic television (1927) | Philo Farnsworth |
| Jun 18 | Movable-type printing press (c.1440) | Johannes Gutenberg |
| Jun 18 | Original Ferris Wheel (1893 Chicago) | George W. Ferris |
| Jun 18 | Safety pin (1849) | Walter Hunt |

### General Trivia
| Jun 18 | Science | Teaspoon of neutron-star material ≈ 6 billion tons |
| Jun 18 | Geography | Russia spans 11 time zones (most of any country) |
| Jun 18 | Food | Carrots were originally purple; orange bred in the Netherlands |
| Jun 18 | Animals | A group of crows is a "murder" |
| Jun 18 | History | Oxford (teaching by 1096) older than Aztec Empire (1325) |
| Jun 18 | Body | Stomach grows a new lining every few days |
| Jun 18 | Astronomy | More stars in the universe than grains of sand on Earth's beaches |
| Jun 18 | Geography | Sahara Desert ≈ size of the continental US |
| Jun 18 | Food | Peanuts are legumes, not nuts |
| Jun 18 | Animals | A shrimp's heart is in its head |
| Jun 18 | Language | The dot over i/j is a "tittle" |
| Jun 18 | History | Great Pyramid was tallest structure for ~3,800 years |

### Songs
| Jun 18 | Bring Me to Life | Evanescence | 2003 |
| Jun 18 | Hey Jealousy | Gin Blossoms | 1992 |
| Jun 18 | Semi-Charmed Life | Third Eye Blind | 1997 |
| Jun 18 | Stay (I Missed You) | Lisa Loeb & Nine Stories | 1994 |
| Jun 18 | Sex and Candy | Marcy Playground | 1997 |
| Jun 18 | You Oughta Know | Alanis Morissette | 1995 |

### This Day in History
| Jun 18 | June 18 (Battle of Waterloo 1815; War of 1812 declared 1812; Sally Ride first American woman in space 1983) | — |
| Jun 18 | National Days: Go Fishing Day; International Picnic Day; National Splurge Day; International Sushi Day; Autistic Pride Day | — |

### Sports / Current Events
| Jun 18 | Sports | FIFA World Cup group stage: Argentina 3-0 Algeria (Messi hat trick, 16th career WC goal), France 3-1 Senegal, England 4-2 Croatia, Ghana 1-0 Panama; USMNT won opener 4-1 vs Paraguay, next vs Australia Fri Jun 19 3 PM ET Lumen Field Seattle |
| Jun 18 | Sports | Golf: U.S. Open begins today at Shinnecock Hills (Southampton, NY), Jun 18-21; Scheffler favorite |
| Jun 18 | Sports | MLB: Brewers best record (45-26) lead NL Central; Reds 5th |
| Jun 18 | Reds | 35-38 5th NL Central 11.0 GB / ~3 GB WC; L-W-L-W-W... last 5 W-L-W-W-L (streak L1); NO game today, next Fri Jun 19 @ NY Yankees 7:05 PM ET |
| Jun 18 | Box Office | Disclosure Day (Spielberg sci-fi) #1, ~$44M open; Toy Story 5 opens Jun 19 ($140M+ projected, franchise record); The Death of Robin Hood (A24, Jackman) also opens Jun 19 |
| Jun 18 | Deaths | David Hockney (88, British pop-art painter / "A Bigger Splash", died Jun 11; confirmed WaPo/NPR/CNN/NBC) |


## June 18, 2026 (v28 — re-run; fresh content, supersedes v27)

### Capitals
| Jun 18 | Alaska | Juneau |
| Jun 18 | Virginia | Richmond |
| Jun 18 | Bolivia | Sucre (constitutional) |
| Jun 18 | Ghana | Accra |

### Classic TV
| Jun 18 | Rawhide (1959–65) | Rowdy Yates | Clint Eastwood |
| Jun 18 | The Avengers (1961–69) | John Steed | Patrick Macnee |
| Jun 18 | Lou Grant (1977–82) | Lou Grant | Ed Asner |
| Jun 18 | The Streets of San Francisco (1972–77) | Det. Lt. Mike Stone | Karl Malden |
| Jun 18 | Scarecrow and Mrs. King (1983–87) | Lee Stetson | Bruce Boxleitner |
| Jun 18 | Picket Fences (1992–96) | Sheriff Jimmy Brock | Tom Skerritt |

### Arts & Literature
| Jun 18 | Creator of Poirot & Miss Marple | Agatha Christie |
| Jun 18 | Waiting for Godot (1953) author | Samuel Beckett |
| Jun 18 | Grids of red/blue/yellow painter | Piet Mondrian |
| Jun 18 | Carmina Burana / "O Fortuna" composer | Carl Orff |
| Jun 18 | Remains of the Day / Never Let Me Go (Nobel 2017) | Kazuo Ishiguro |
| Jun 18 | Doctor Zhivago author (Nobel 1958) | Boris Pasternak |

### Founded & Invented
| Jun 18 | Tesla Motors founded | 2003 (Eberhard & Tarpenning) |
| Jun 18 | Cotton gin (1793) | Eli Whitney |
| Jun 18 | Telegraph / Morse code | Samuel Morse |
| Jun 18 | Ben & Jerry's founded | 1978 (Burlington VT gas station) |
| Jun 18 | Lockstitch sewing machine (1846) | Elias Howe |
| Jun 18 | Gmail public launch | 2004 (April 1, 1 GB) |

### General Trivia
| Jun 18 | Science | Lightning bolt could toast ~100,000 slices of bread |
| Jun 18 | Animals | A group of jellyfish is a "smack" |
| Jun 18 | Geography | Africa is the only continent in all four hemispheres |
| Jun 18 | Food | Pineapple's bromelain digests protein as you eat it |
| Jun 18 | Astronomy | A day on Mercury (~176 Earth days) is longer than its year |
| Jun 18 | Biology | Roughly as many bacterial cells as human cells in the body |
| Jun 18 | History | The Hundred Years' War lasted 116 years (1337–1453) |
| Jun 18 | Tech | First webcam (Cambridge 1991) watched a coffee pot |
| Jun 18 | Animals | Sea otters have the densest fur (~1M hairs/sq in) |
| Jun 18 | Geography | Istanbul straddles Europe and Asia |
| Jun 18 | Language | "Alphabet" = alpha + beta (first two Greek letters) |

### This Day in History
| Jun 18 | June 18 (de Gaulle "Appeal of 18 June" 1940; Monterey Pop Festival closes 1967; Carter–Brezhnev sign SALT II 1979) | — |
| Jun 18 | National Days: International Panic Day; National Wanna Get Away Day; Go Fishing Day; International Picnic Day | — |

### Sports / Current Events
| Jun 18 | Sports | World Cup group stage: Norway 4-1 Iraq, Austria 3-1 Jordan (Jun 16); Colombia 3-1 Uzbekistan, Portugal 1-1 DR Congo (Jun 17); Jun 18 fixtures Mexico-Korea & Canada-Qatar; USMNT next vs Australia Jun 19 Seattle |
| Jun 18 | Sports | Golf: 126th U.S. Open opens at Shinnecock Hills; fog-delayed R1, Sam Stevens 2-under clubhouse leader, McIlroy 69 |
| Jun 18 | Sports | NBA: Knicks champions (4-1 over Spurs), Brunson Finals MVP, first NY title since 1973; NHL: Hurricanes win Stanley Cup over Vegas 4-2, Jordan Staal oldest Conn Smythe winner |
| Jun 18 | Reds | 35-38, 5th NL Central ~11 GB; W-L-W-W-L last 5; won 2 of 3 vs Mets (12-0, 5-3) then lost finale 1-9 Jun 17; NO game today, next Fri Jun 19 @ NY Yankees 7:05 PM ET |
| Jun 18 | Box Office | Disclosure Day (Spielberg sci-fi) #1, $44.5M opening; reunites Spielberg/Koepp/Williams, shot in-camera; Blunt & O'Connor lead |
| Jun 18 | Deaths | Walter Parazaider (81, Chicago saxophonist, Jun 17); Tom Dreesen (86, comedian/Sinatra opener, Jun 17); Daveigh Chase (36, The Ring/Lilo & Stitch, Jun 16); Abdullah Ibrahim (91, SA jazz pianist, Jun 15) |


## June 22, 2026 (v29)

### Capitals
| Jun 22 | Mali | Bamako |
| Jun 22 | Tonga | Nuku'alofa |
| Jun 22 | Côte d'Ivoire (Ivory Coast) | Yamoussoukro (Abidjan largest city) |
| Jun 22 | Georgia (country) | Tbilisi |

### Classic TV
| Jun 22 | Gunsmoke (1955–75) | Marshal Matt Dillon | James Arness |
| Jun 22 | The Honeymooners (1955–56) | Ralph Kramden | Jackie Gleason |
| Jun 22 | Hogan's Heroes (1965–71) | Col. Robert Hogan | Bob Crane |
| Jun 22 | I Dream of Jeannie (1965–70) | Jeannie | Barbara Eden |
| Jun 22 | The Waltons (1972–81) | John-Boy Walton | Richard Thomas |
| Jun 22 | Adam-12 (1968–75) | Officer Pete Malloy | Martin Milner |

### Arts & Literature
| Jun 22 | Pride and Prejudice (1813) author | Jane Austen |
| Jun 22 | The Old Man and the Sea author | Ernest Hemingway |
| Jun 22 | American Gothic (1930) painter | Grant Wood |
| Jun 22 | "New World Symphony" (No. 9, 1893) composer | Antonín Dvořák |
| Jun 22 | Crime and Punishment (1866) author | Fyodor Dostoevsky |
| Jun 22 | "The Road Not Taken" poet | Robert Frost |

### Founded & Invented
| Jun 22 | Jet engine patent (1930) | Sir Frank Whittle (von Ohain independent in Germany) |
| Jun 22 | Roomba robot vacuum (2002) | iRobot |
| Jun 22 | Vacuum flask / Thermos (1892) | Sir James Dewar |
| Jun 22 | Game Boy (1989) | Nintendo / Gunpei Yokoi |
| Jun 22 | Pop-Tarts (1964) | Kellogg's |
| Jun 22 | Transistor (1947) | Bardeen, Brattain & Shockley (Bell Labs) |

### General Trivia
| Jun 22 | Animals | Hummingbirds are the only birds that can fly backward |
| Jun 22 | Geography | Vatican City is the world's smallest country (~0.49 km²) |
| Jun 22 | Nature | More trees on Earth (~3T) than stars in the Milky Way (~100–400B) |
| Jun 22 | Language | Fear of long words = "hippopotomonstrosesquippedaliophobia" |
| Jun 22 | History | Statue of Liberty's official name: "Liberty Enlightening the World" |
| Jun 22 | Food | Almonds aren't true nuts — seeds of a drupe (stone fruit) |
| Jun 22 | Animals | Elephants are the only mammal that can't jump |
| Jun 22 | Astronomy | The Moon drifts ~3.8 cm farther from Earth each year |
| Jun 22 | Body | Babies born with ~300 bones; adults have 206 (they fuse) |
| Jun 22 | Astronomy | No sound in space — a vacuum can't carry sound waves |
| Jun 22 | Science | The Sun is actually white; atmosphere scatters light to look yellow |
| Jun 22 | Body | Every person's tongue print is unique, like a fingerprint |

### This Day in History
| Jun 22 | June 22 (Operation Barbarossa — Germany invades USSR 1941; FDR signs G.I. Bill 1944; Maradona "Hand of God" goal vs England 1986) | — |
| Jun 22 | National Days: National Onion Ring Day; National Chocolate Éclair Day; Take Your Cat to Work Day; World Rainforest Day | — |

### Sports / Current Events
| Jun 22 | Sports | World Cup group stage: Argentina 2-0 Austria (Messi brace → all-time WC scoring record, 18 goals); France led Iraq 1-0; USMNT clinched group with 2-0 win over Australia (Jun 19 Seattle) |
| Jun 22 | Sports | Golf: Wyndham Clark won 126th U.S. Open at Shinnecock Hills (Jun 21), wire-to-wire, beat Sam Burns by one at 4-under; 2nd U.S. Open in 3 yrs |
| Jun 22 | Reds | 37-39, 5th NL Central; last 5 W-L-L-W-W (streak W2); took 2 of 3 at NYY (L 5-0, W 10-2, W 4-1 — Chase Burns 8th straight win); TODAY vs Brewers 7:10 PM ET (Singer vs Woodruff) |
| Jun 22 | Box Office | Toy Story 5 #1, $160M domestic open (biggest of 2026; franchise record; 2nd-biggest animated open ever); $312M global; Taylor Swift #1 song "I Knew It, I Knew You" |
| Jun 22 | Deaths | James Burrows (85, legendary TV director / Cheers co-creator, Jun 19); Daveigh Chase (36, The Ring/Lilo, Jun 16); Tom Dreesen (86, comedian, Jun 17); Abdullah Ibrahim (91, SA jazz pianist, Jun 15) |


## June 23, 2026 (v30)

### Capitals
| Jun 23 | Utah | Salt Lake City |
| Jun 23 | Poland | Warsaw |
| Jun 23 | Alabama | Montgomery |
| Jun 23 | Philippines | Manila |

### Classic TV
| Jun 23 | Petticoat Junction (1963–70) | Kate Bradley | Bea Benaderet |
| Jun 23 | Have Gun – Will Travel (1957–63) | Paladin | Richard Boone |
| Jun 23 | Dark Shadows (1966–71) | Barnabas Collins | Jonathan Frid |
| Jun 23 | Kung Fu (1972–75) | Kwai Chang Caine | David Carradine |
| Jun 23 | Soap (1977–81) | Jessica Tate | Katherine Helmond |
| Jun 23 | Cannon (1971–76) | Frank Cannon | William Conrad |

### Arts & Literature
| Jun 23 | The Scarlet Letter (1850) author | Nathaniel Hawthorne |
| Jun 23 | The Canterbury Tales author | Geoffrey Chaucer |
| Jun 23 | Gone with the Wind (1936) author | Margaret Mitchell |
| Jun 23 | The Garden of Earthly Delights painter | Hieronymus Bosch |
| Jun 23 | "The Planets" suite composer | Gustav Holst |
| Jun 23 | "Howl" (1956) poet | Allen Ginsberg |

### Founded & Invented
| Jun 23 | Penicillin discovered (1928) | Alexander Fleming |
| Jun 23 | Vaseline / petroleum jelly (1872) | Robert Chesebrough |
| Jun 23 | Practical light bulb (1879) | Thomas Edison |
| Jun 23 | Ferrari founded | Enzo Ferrari (1939) |
| Jun 23 | IBM founded | 1911 (renamed IBM 1924) |
| Jun 23 | Bagless cyclone vacuum (1991) | James Dyson |

### General Trivia
| Jun 23 | Geography | Pacific Ocean wider than the Moon's diameter |
| Jun 23 | History | Cleopatra lived closer to the Moon landing than to the Pyramids |
| Jun 23 | Astronomy | Saturn is less dense than water — it would float |
| Jun 23 | Animals | A group of owls is a "parliament" |
| Jun 23 | Animals | Wombats produce cube-shaped droppings |
| Jun 23 | Geography | Canada has more lakes than all other countries combined |
| Jun 23 | Food | Ketchup was sold in the 1830s as medicine |
| Jun 23 | Body | The nose can distinguish over a trillion scents |
| Jun 23 | Science | Bananas are slightly radioactive (potassium-40) |
| Jun 23 | Language | "Set" has the most definitions of any English word |
| Jun 23 | Animals | Cows form "best friend" bonds |
| Jun 23 | Science | It rains diamonds inside Neptune and Uranus |

### This Day in History
| Jun 23 | June 23 (Typewriter patented 1868; IOC founded 1894; Title IX 1972; Batman 1989) | — |
| Jun 24 | June 24 (Battle of Bannockburn 1314; Kenneth Arnold "flying saucers" 1947; Berlin Blockade begins 1948; Isner–Mahut longest tennis match 2010) | — |
| Jun 23 | National Days: National Pink Day; National Detroit-Style Pizza Day; National Hydration Day; Pink Flamingo Day; International Widows' Day | — |

### Sports / Current Events
| Jun 23 | Reds | 37-40, 5th NL Central ~10.5 GB; last 5 L-L-W-W-L (streak L1); split @ NYY (L 0-5, W 10-2, W 4-1), lost Brewers opener 1-2/10 (Woodruff perfect into 6th); TODAY vs Brewers 7:10 PM ET |
| Jun 23 | Box Office | Toy Story 5 #1, $160M domestic open / $312M global; 2nd-biggest Pixar opening ever (behind Incredibles 2 $182.7M) |
| Jun 23 | Sports | World Cup group stage: Argentina 2-0 Austria (Messi), France 3-0 Iraq, Portugal 5-0 Uzbekistan, Norway 3-2 Senegal, Algeria 2-1 Jordan; MLB Brewers 47-29 best record in baseball (franchise-best start) |
| Jun 23 | Deaths | Clive Davis (94, music exec Columbia/Arista — Whitney Houston, Springsteen, Joplin, Santana, Jun 22); Stacey King (59, 3x champ Bulls / Wolves broadcaster); James Burrows (85, Cheers director, Jun 19); Daveigh Chase (36, The Ring/Lilo, Jun 16) |
| Jun 23 | News | US-Iran talks in Switzerland show progress (inspectors to return); Lebanon ceasefire talks; UK PM Keir Starmer resigned; Bolivia state of emergency |


## June 24, 2026 (v31)

### Capitals
| Jun 24 | Arizona | Phoenix |
| Jun 24 | North Carolina | Raleigh |
| Jun 24 | Chile | Santiago |
| Jun 24 | Indonesia | Jakarta |

### Classic TV
| Jun 24 | Leave It to Beaver (1957–63) | Ward Cleaver | Hugh Beaumont |
| Jun 24 | Gomer Pyle, U.S.M.C. (1964–69) | Gomer Pyle | Jim Nabors |
| Jun 24 | The Partridge Family (1970–74) | Shirley Partridge | Shirley Jones |
| Jun 24 | The Streets of San Francisco (1972–77) | Det. Lt. Mike Stone | Karl Malden |
| Jun 24 | Baretta (1975–78) | Det. Tony Baretta | Robert Blake |
| Jun 24 | The Phil Silvers Show (1955–59) | Sgt. Ernie Bilko | Phil Silvers |

### Arts & Literature
| Jun 24 | The Handmaid's Tale (1985) author | Margaret Atwood |
| Jun 24 | A Doll's House (1879) playwright | Henrik Ibsen |
| Jun 24 | De Stijl grid abstraction painter | Piet Mondrian |
| Jun 24 | "Carmina Burana" (1936) composer | Carl Orff |
| Jun 24 | Oedipus Rex tragedian | Sophocles |
| Jun 24 | Dune (1965) author | Frank Herbert |

### Founded & Invented
| Jun 24 | First gasoline automobile patent (1886) | Karl Benz |
| Jun 24 | Safety razor inventor | King C. Gillette (1901; sold 1903) |
| Jun 24 | KFC founder | Colonel Harland Sanders (first franchise 1952) |
| Jun 24 | First powered airplane flight (1903) | Wright Brothers |
| Jun 24 | Lamborghini founded (1963) | Ferruccio Lamborghini |
| Jun 24 | Lockstitch sewing machine patent (1846) | Elias Howe |

### General Trivia
| Jun 24 | Animals | Sea otters store a favorite rock in a skin pouch under the forearm |
| Jun 24 | Geography | Istanbul is the only major city on two continents (Europe & Asia) |
| Jun 24 | Science | Hottest air temp on record: 134°F, Death Valley (1913) |
| Jun 24 | Food | A honeybee visits ~2 million flowers per pound of honey |
| Jun 24 | Animals | A group of jellyfish is a "smack" |
| Jun 24 | History | The Hundred Years' War lasted 116 years (1337–1453) |
| Jun 24 | Body | Adult body holds enough iron to make a ~3-inch nail |
| Jun 24 | Astronomy | One day on Mercury lasts ~176 Earth days |
| Jun 24 | Language | No perfect rhyme for month, orange, silver, purple |
| Jun 24 | Food | Tomatoes once feared as "poison apples" (lead from pewter plates) |
| Jun 24 | Science | Glass is an "amorphous solid" |
| Jun 24 | Animals | A blue whale's tongue can weigh as much as an elephant |

### Music (1990–2010)
| Jun 24 | More Than Words | Extreme | 1990 |
| Jun 24 | Loser | Beck | 1994 |
| Jun 24 | I Don't Want to Miss a Thing | Aerosmith | 1998 |
| Jun 24 | All the Small Things | Blink-182 | 1999 |
| Jun 24 | The Reason | Hoobastank | 2003 |
| Jun 24 | Rehab | Amy Winehouse | 2006 |

### This Day in History
| Jun 24 | June 24 (Battle of Bannockburn 1314; Kenneth Arnold "flying saucers" 1947; Berlin Blockade begins 1948; Isner–Mahut longest tennis match 2010) | — |
| Jun 24 | National Days: World UFO Day; International Fairy Day; National Pralines Day; Celebration of the Senses; Swim a Lap Day; National Parchment Day; St. John's Day (Midsummer) | — |

### Sports / Current Events
| Jun 24 | Reds | 37-41, 5th NL Central 11.5 GB (Brewers 48-29); last 5 L-W-W-L-L (streak L2); took 2 of 3 @ NYY (L 0-5, W 10-2, W 4-1), lost first two vs Brewers (1-2, 0-2); TONIGHT vs Brewers 7:10 PM ET (Game 3 of 3) |
| Jun 24 | Box Office | Toy Story 5 #1; $160M domestic / $312M global open; passed $200M domestic in 5 days; biggest 2026 open; franchise record (> Toy Story 4 $120.9M) |
| Jun 24 | Sports | World Cup final group games (R32 begins Jun 28): England 0-0 Ghana, Portugal 5-0 Uzbekistan, Croatia 1-0 Panama, Colombia 1-0 DR Congo; USMNT clinched, leads Group D vs Turkiye; Brewers 48-29 best record in MLB; Wyndham Clark won U.S. Open |
| Jun 24 | Deaths | Alan Greenspan (100, Fed Chair 1987-2006, Jun 22); Clive Davis (94, music exec, Jun 22); Stacey King (59, Bulls champ/broadcaster) |
| Jun 24 | News | US-Iran nuclear inspector talks progress; Lebanon ceasefire talks; UK PM Keir Starmer resigned; Bolivia state of emergency |



## June 25, 2026 (v32)

### Capitals
| Jun 25 | Oman | Muscat |
| Jun 25 | North Macedonia | Skopje |
| Jun 25 | Moldova | Chișinău |
| Jun 25 | Mauritania | Nouakchott |

### Classic TV
| Jun 25 | Mama's Family (1983–90) | Thelma "Mama" Harper | Vicki Lawrence |
| Jun 25 | Sledge Hammer! (1986–88) | Inspector Sledge Hammer | David Rasche |
| Jun 25 | Sabrina the Teenage Witch (1996–2003) | Sabrina Spellman | Melissa Joan Hart |
| Jun 25 | Everybody Loves Raymond (1996–2005) | Ray Barone | Ray Romano |
| Jun 25 | The King of Queens (1998–2007) | Doug Heffernan | Kevin James |
| Jun 25 | Dharma & Greg (1997–2002) | Dharma Finkelstein | Jenna Elfman |

### Arts & Literature
| Jun 25 | Shakespeare play with "To be, or not to be" | Hamlet |
| Jun 25 | A Christmas Carol (1843) author | Charles Dickens |
| Jun 25 | "The Last Supper" mural painter | Leonardo da Vinci |
| Jun 25 | "The Tortoise and the Hare" / fables | Aesop |
| Jun 25 | "Also sprach Zarathustra" (2001 fanfare) composer | Richard Strauss |
| Jun 25 | The Wonderful Wizard of Oz (1900) author | L. Frank Baum |

### Founded & Invented
| Jun 25 | First practical helicopter (1939) | Igor Sikorsky |
| Jun 25 | Tea bag (1908, accidental) | Thomas Sullivan |
| Jun 25 | Teddy bear (1902) named after | Theodore Roosevelt (Morris Michtom) |
| Jun 25 | Ice cream cone popularized at | 1904 St. Louis World's Fair |
| Jun 25 | Graham cracker named for | Rev. Sylvester Graham |
| Jun 25 | Compound microscope (~1590s) | Zacharias Janssen (credited) |

### General Trivia
| Jun 25 | Animals | Goats have rectangular pupils for a wide panoramic view |
| Jun 25 | Body | Stomach acid is strong enough to dissolve a razor blade |
| Jun 25 | Science | A single cumulus cloud can weigh more than a million pounds |
| Jun 25 | Geography | Alaska is both the westernmost and easternmost US state (Aleutians cross 180°) |
| Jun 25 | Food | White chocolate isn't technically chocolate — no cocoa solids |
| Jun 25 | Did You Know | Impossible to hum while holding your nose closed |
| Jun 25 | Geography | France spans 12 time zones — most of any country (overseas territories) |
| Jun 25 | Biology | Mushrooms are more closely related to animals than to plants |
| Jun 25 | Body | You can't tickle yourself — the cerebellum predicts the sensation |
| Jun 25 | Animals | Owls can rotate their heads about 270 degrees |
| Jun 25 | Science | A teaspoon of soil holds more microbes than there are people on Earth |
| Jun 25 | Geography | Canada has the longest coastline of any country (~243,000 km) |

### This Day in History
| Jun 25 | June 25 (Battle of the Little Bighorn / Custer's Last Stand 1876; Korean War begins 1950; Kim Campbell first female Canadian PM 1993) | — |
| Jun 25 | National Days: National Catfish Day; National Bomb Pop Day; Global Beatles Day; Color TV Day; National Handshake Day; Leon Day | — |

### Sports / Current Events
| Jun 25 | Reds | 37-42, 5th NL Central ~12.5 GB (Brewers 49-29, best in MLB); last 5 W-W-L-L-L (streak L3); Brewers completed 3-game sweep at GABP (L 1-2/10, L 0-2, L 5-6); NO GAME TODAY (off day), next Fri Jun 26 @ Pirates |
| Jun 25 | Box Office | Toy Story 5 #1; $160M domestic / $312M global open (biggest of 2026; franchise record > Toy Story 4 $120.9M); 2nd-biggest Pixar open behind Incredibles 2 |
| Jun 25 | Sports | World Cup group stage wrapping (R32 begins Jun 28): USMNT clinched Group D (4-1 Paraguay, 2-0 Australia), play Türkiye tonight; Jun 24 — Brazil 3-0 Scotland, Mexico 3-0 Czechia, Morocco 4-2 Haiti, Switzerland 3-1 Qatar; NBA Draft — Wizards take AJ Dybantsa (BYU) No.1, Peterson #2, Boozer #3 |
| Jun 25 | Deaths | Alan Greenspan (100, Fed Chair 1987-2006, Jun 22); Clive Davis (94, music exec, Jun 22); Denisa Baránková (24, Slovak Olympic archer, Jun 25) |
| Jun 25 | News | US-Iran inspectors to return under interim deal (oil prices fall); Venezuela 7.2 & 7.5 earthquakes (Jun 24); DR Congo Ebola 1,000+ cases/250+ deaths; UK/Spain extreme-heat red alerts |

## June 29, 2026 (v33)

### Capitals
| Jun 29 | Panama | Panama City |
| Jun 29 | Zambia | Lusaka |
| Jun 29 | Uzbekistan | Tashkent |
| Jun 29 | Fiji | Suva |

### Classic TV
| Jun 29 | Daniel Boone (1964–70) | Daniel Boone | Fess Parker |
| Jun 29 | The Patty Duke Show (1963–66) | Patty & Cathy Lane | Patty Duke |
| Jun 29 | Car 54, Where Are You? (1961–63) | Officer Gunther Toody | Joe E. Ross |
| Jun 29 | Chico and the Man (1974–78) | Chico Rodriguez | Freddie Prinze |
| Jun 29 | Vega$ (1978–81) | Dan Tanna | Robert Urich |
| Jun 29 | 227 (1985–90) | Mary Jenkins | Marla Gibbs |

### Arts & Literature
| Jun 29 | Creator of spy James Bond (novels) | Ian Fleming |
| Jun 29 | Treasure Island / Dr. Jekyll and Mr. Hyde author | Robert Louis Stevenson |
| Jun 29 | Portnoy's Complaint / American Pastoral author | Philip Roth |
| Jun 29 | "Christina's World" (1948) painter | Andrew Wyeth |
| Jun 29 | "Father of the Symphony" / "Surprise" Symphony | Joseph Haydn |
| Jun 29 | "How do I love thee?" poet | Elizabeth Barrett Browning |

### Founded & Invented
| Jun 29 | Intel founded | 1968 (Noyce & Moore) |
| Jun 29 | Dell founded in dorm | 1984 (Michael Dell) |
| Jun 29 | Telescope (1608) | Hans Lippershey |
| Jun 29 | Piano (early 1700s) | Bartolomeo Cristofori |
| Jun 29 | Potato chip (1853) | George Crum |
| Jun 29 | Passenger elevator safety brake (1853) | Elisha Otis |

### General Trivia
| Jun 29 | Food | Honey never spoils — 3,000-yr-old edible honey in Egyptian tombs |
| Jun 29 | Animals | An octopus has three hearts and blue (copper-based) blood |
| Jun 29 | Science | Eiffel Tower grows ~15 cm taller in summer (iron expands) |
| Jun 29 | Language | A "jiffy" is a real time unit (~1/100 second) |
| Jun 29 | Did You Know | Scotland's national animal is the unicorn |
| Jun 29 | Animals | Bats are the only mammals capable of true sustained flight |
| Jun 29 | History | Shortest war: Anglo-Zanzibar (1896) lasted ~38 minutes |
| Jun 29 | Astronomy | Venus is the only planet that rotates clockwise (retrograde) |
| Jun 29 | Language | The dot over an "i"/"j" is called a "tittle" |
| Jun 29 | Food | Bananas/avocados/watermelons are berries; strawberries aren't |
| Jun 29 | Nature | Sharks (~450M yrs) are older than trees (~390M yrs) |

### Songs (1990–2010)
| Jun 29 | Linger | The Cranberries | 1993 |
| Jun 29 | 3AM | Matchbox Twenty | 1996 |
| Jun 29 | Breakfast at Tiffany's | Deep Blue Something | 1995 |
| Jun 29 | Take Me Out | Franz Ferdinand | 2004 |
| Jun 29 | Chasing Cars | Snow Patrol | 2006 |
| Jun 29 | Are You Gonna Be My Girl | Jet | 2003 |

### This Day in History
| Jun 29 | June 29 (Globe Theatre fire during Henry VIII 1613; Federal-Aid Highway Act / Interstate System 1956; Atlantis docks with Mir 1995) | — |
| Jun 29 | National Days: National Camera Day; National Waffle Iron Day; National Almond Buttercrunch Day; International Mud Day; Feast of Saints Peter & Paul | — |

### Sports / Current Events
| Jun 29 | Reds | 39-43, 5th NL Central 11.5 GB (Brewers 50-31); last 5 L-L-W-W-L (streak L1); won 2 of 3 @ Pirates (W 6-4, W 9-7, L 4-9); TODAY @ Brewers 7:40 PM ET |
| Jun 29 | Box Office | Toy Story 5 #1 2nd weekend ~$70M (held off Supergirl ~$38M debut); $585M worldwide, nearing $300M domestic; -56% drop mirrors Incredibles 2 |
| Jun 29 | Sports | World Cup R32: Canada 1-0 South Africa (Jun 28, first R32 match), Brazil 2-1 Japan (Jun 29 Martinelli winner); Wimbledon begins (Sinner/Sabalenka headline); Brewers 50-31 2nd-best in MLB (Misiorowski NL Cy Young front-runner) |
| Jun 29 | Deaths | David Clayton-Thomas (84, Blood Sweat & Tears singer, Jun 24); Ann Blyth (98, Mildred Pierce actress, Jun 24); Mignon Dunn (94, Met Opera mezzo, Jun 28); Om Malik (59, GigaOm founder, Jun 24) |
| Jun 29 | News | UK PM Keir Starmer resigned; US-Iran inspectors returning under interim deal (oil prices ease); DR Congo Ebola 1,000+ cases/250+ deaths; Venezuela recovery after 7.2/7.5 quakes |



## June 30, 2026 (v34)

### Capitals
| Jun 30 | Egypt | Cairo |
| Jun 30 | New Zealand | Wellington |
| Jun 30 | Kazakhstan | Astana |
| Jun 30 | Oregon | Salem |

### Classic TV
| Jun 30 | Mannix (1967–75) | Joe Mannix | Mike Connors |
| Jun 30 | Ironside (1967–75) | Chief Robert Ironside | Raymond Burr |
| Jun 30 | Kojak (1973–78) | Lt. Theo Kojak | Telly Savalas |
| Jun 30 | Family Ties (1982–89) | Alex P. Keaton | Michael J. Fox |
| Jun 30 | Knight Rider (1982–86) | Michael Knight | David Hasselhoff |
| Jun 30 | MacGyver (1985–92) | Angus MacGyver | Richard Dean Anderson |

### Arts & Literature
| Jun 30 | The Grapes of Wrath / Of Mice and Men author | John Steinbeck |
| Jun 30 | The Catcher in the Rye (1951) author | J.D. Salinger |
| Jun 30 | "Girl with a Pearl Earring" painter | Johannes Vermeer |
| Jun 30 | "The Card Players" / Mont Sainte-Victoire painter | Paul Cézanne |
| Jun 30 | "The Four Seasons" composer | Antonio Vivaldi |
| Jun 30 | Slaughterhouse-Five author | Kurt Vonnegut |

### Founded & Invented
| Jun 30 | Microwave oven (1945, accidental) | Percy Spencer |
| Jun 30 | Riveted blue jeans patent (1873) | Levi Strauss & Jacob Davis |
| Jun 30 | Velcro (inspired by burrs) | George de Mestral |
| Jun 30 | Coca-Cola first sold (1886) | John Pemberton |
| Jun 30 | Nike / Blue Ribbon Sports (1964) | Phil Knight & Bill Bowerman |
| Jun 30 | Slinky (1943) | Richard James |

### General Trivia
| Jun 30 | Geography | Sargasso Sea is the only sea with no land borders (defined by currents) |
| Jun 30 | Animals | A group of pugs is called a "grumble" |
| Jun 30 | Body | Brain is ~2% of body weight but uses ~20% of energy |
| Jun 30 | Language | "Typewriter" can be typed using only the top QWERTY row |
| Jun 30 | Food | Apples are ~25% air, which is why they float |
| Jun 30 | Science | Bubble wrap was originally invented (1957) as 3-D wallpaper |
| Jun 30 | Astronomy | Some neutron stars spin up to ~700 times per second |
| Jun 30 | Nature | Lightning strikes Earth ~8 million times per day |
| Jun 30 | Did You Know | World's shortest scheduled flight (Westray–Papa Westray) under 90 seconds |
| Jun 30 | Animals | A snail can stay dormant for up to three years |
| Jun 30 | Math | A shuffled 52-card deck has ~8×10⁶⁷ possible orders (likely never repeated) |

### Songs (1990–2010)
| Jun 30 | Plush | Stone Temple Pilots | 1992 |
| Jun 30 | Santa Monica | Everclear | 1995 |
| Jun 30 | Steal My Sunshine | Len | 1999 |
| Jun 30 | The Scientist | Coldplay | 2002 |
| Jun 30 | By the Way | Red Hot Chili Peppers | 2002 |
| Jun 30 | Such Great Heights | The Postal Service | 2003 |

### This Day in History
| Jun 30 | June 30 (Tunguska event 1908; Night of the Long Knives 1934; first Corvette rolls off line in Flint 1953) | — |
| Jun 30 | National Days: Social Media Day; National Meteor Watch Day; International Asteroid Day; National Corvette Day; DR Congo Independence Day | — |

### Sports / Current Events
| Jun 30 | Reds | 39-44, 5th NL Central 12.5 GB (Brewers 51-31); last 5 L-W-W-L-L (streak L2); won 2 of 3 @ Pirates (W 6-4, W 9-7, L 4-9) then lost Brewers opener 3-5; TODAY @ Brewers 7:40 PM ET (Lowder vs Sproat, American Family Field) |
| Jun 30 | Box Office | Toy Story 5 #1 2nd weekend ~$70M (-55%); Supergirl flopped $37-38M open ($170M budget, B- CinemaScore), first DCU film to open behind a holdover; Toy Story 5 $585M+ worldwide |
| Jun 30 | Sports | World Cup R32: Paraguay over Germany on PKs, Morocco over Netherlands on PKs (Bounou), Brazil 2-1 Japan (Martinelli 95'); Jun 30 — Côte d'Ivoire-Norway, France-Sweden, Mexico-Ecuador; Wimbledon underway (Serena wildcard; Ben Shelton upset by Otto Virtanen); Brewers 51-31 best NL record; Mets' Semien out 4-6 wks (hip flexor) |
| Jun 30 | Deaths | Dame Penelope Keith (86, The Good Life/To the Manor Born, Jun 29); Waldo Urrego (80, Colombian actor, Jun 27); Eeva Kilpi (97, Finnish poet/novelist, Jun 27); K. Bhagyaraj (72, Tamil cinema director, Jun 27) |
| Jun 30 | News | SCOTUS rejected ending birthright citizenship; SCOTUS 6-3 struck down party coordinated-spending limits; Putin admits Russian fuel shortages from Ukrainian refinery strikes; European heat-wave health alerts |

## July 2, 2026 (v35)

### Capitals
| Jul 2 | Virginia | Richmond |
| Jul 2 | Alaska | Juneau |
| Jul 2 | Austria | Vienna |
| Jul 2 | Laos | Vientiane |

### Classic TV
| Jul 2 | Combat! (1962-67) | Sgt. Chip Saunders | Vic Morrow |
| Jul 2 | Marcus Welby, M.D. (1969-76) | Dr. Marcus Welby | Robert Young |
| Jul 2 | Emergency! (1972-77) | Paramedic John Gage | Randolph Mantooth |
| Jul 2 | Little House on the Prairie (1974-83) | Charles Ingalls | Michael Landon |
| Jul 2 | The Facts of Life (1979-88) | Edna Garrett | Charlotte Rae |
| Jul 2 | In the Heat of the Night (1988-95) | Chief Bill Gillespie | Carroll O'Connor |

### Arts & Literature
| Jul 2 | Waiting for Godot (1953) playwright | Samuel Beckett |
| Jul 2 | The Count of Monte Cristo / Three Musketeers author | Alexandre Dumas |
| Jul 2 | The Time Machine / The War of the Worlds author | H.G. Wells |
| Jul 2 | La boheme / Madama Butterfly composer | Giacomo Puccini |
| Jul 2 | Oversized flowers / New Mexico desert painter | Georgia O'Keeffe |
| Jul 2 | "I Wandered Lonely as a Cloud" (daffodils) poet | William Wordsworth |

### Founded & Invented
| Jul 2 | Telegraph + Morse code inventor | Samuel Morse (1830s-40s) |
| Jul 2 | First smallpox vaccine (1796) | Edward Jenner |
| Jul 2 | Cotton gin (1793) | Eli Whitney |
| Jul 2 | Radio / first transatlantic signal (1901) | Guglielmo Marconi |
| Jul 2 | Samsung founded | 1938 (South Korea) |
| Jul 2 | Tesla Motors founded | 2003 (Eberhard & Tarpenning) |

### General Trivia
| Jul 2 | Astronomy | Uranus is tipped ~98 deg on its side, rolling around the Sun |
| Jul 2 | Geography | Africa is the only continent in all four hemispheres |
| Jul 2 | Animals | A group of rhinoceroses is a "crash" |
| Jul 2 | History | 1932 "Great Emu War" - Australia deployed troops against emus and lost |
| Jul 2 | Language | "Quarantine" from Italian quaranta giorni = "forty days" |
| Jul 2 | Botany | Bamboo is fastest-growing plant - up to ~35 in (90 cm) per day |
| Jul 2 | Food | Fear of peanut butter on roof of mouth = arachibutyrophobia |
| Jul 2 | Nature | ~3 trillion trees on Earth - more than stars in the Milky Way |
| Jul 2 | Did You Know | The "S" in Harry S. Truman doesn't stand for anything |
| Jul 2 | Tech | World's first webcam (Cambridge 1991) watched a coffee pot |
| Jul 2 | Body | The human eye can distinguish ~10 million colors |

### Songs (1990-2010)
| Jul 2 | No Rain | Blind Melon | 1992 |
| Jul 2 | Champagne Supernova | Oasis | 1996 |
| Jul 2 | Say It Ain't So | Weezer | 1994 |
| Jul 2 | Cannonball | The Breeders | 1993 |
| Jul 2 | Fake Plastic Trees | Radiohead | 1995 |
| Jul 2 | Ocean Avenue | Yellowcard | 2003 |

### This Day in History
| Jul 2 | July 2 (Continental Congress votes for independence 1776; Amelia Earhart vanishes 1937; LBJ signs Civil Rights Act 1964) | - |
| Jul 2 | National Days: World UFO Day; National Anisette Day; National Wildland Firefighter Day; National I Forgot Day; Made in the USA Day | - |

### Sports / Current Events
| Jul 2 | Reds | 40-46, 5th NL Central 13.5 GB (Brewers 53-32); last 5 L-L-L-L-W (W1); split DH @ Brewers today (L 2-4, W 7-2) after taking 2 of 3 @ Pirates then dropping 2 to open Milwaukee series |
| Jul 2 | Box Office | Toy Story 5 #1 2nd weekend (Jun 26-28) ~$70.8M (-56%), $298M domestic; Supergirl $37M open; Jackass: Best and Last new |
| Jul 2 | Sports | World Cup knockouts: USA 2-0 Bosnia, England 2-1 DR Congo, Belgium 3-2 Senegal (AET); R16 began Jul 2. Wimbledon: Ben Shelton (4) upset by Otto Virtanen, Svitolina (8) out, Serena on wildcard. NBA FA: (reported) Jaylen Brown to 76ers for Paul George, LeBron leaves Lakers (land Walker Kessler), Norman Powell to Bulls. MLB: Brewers 53-32 best record |
| Jul 2 | Deaths | Victor Willis (74, Village People lead singer / "YMCA" co-writer, Jun 30); David Clayton-Thomas (84, Blood Sweat & Tears, Jun 24); Ann Blyth (98, Mildred Pierce actress, Jun 24); Om Malik (59, tech journalist/GigaOm, Jun 24) |
| Jul 2 | News | Eastern US record heat dome; Trump vows long July 4 (250th) National Mall speech; heavy Russian strikes on Kyiv; Pope Leo excommunicates SSPX members; US-Iran talks show "positive progress" via Qatar/Pakistan mediators |

## July 3, 2026 (v36)

### Capitals
| Jul 3 | Bosnia & Herzegovina | Sarajevo |
| Jul 3 | Moldova | Chișinău |
| Jul 3 | Bahrain | Manama |
| Jul 3 | The Bahamas | Nassau |

### Classic TV
| Jul 3 | The Adventures of Rin Tin Tin (1954–59) | Corporal Rusty | Lee Aaker |
| Jul 3 | Lassie (1954–73) | Timmy Martin | Jon Provost |
| Jul 3 | Wagon Train (1957–65) | Major Seth Adams | Ward Bond |
| Jul 3 | The Green Hornet (1966–67) | Kato | Bruce Lee |
| Jul 3 | The Flying Nun (1967–70) | Sister Bertrille | Sally Field |
| Jul 3 | Kolchak: The Night Stalker (1974–75) | Carl Kolchak | Darren McGavin |

### Arts & Literature
| Jul 3 | Anne of Green Gables (1908) author | L.M. Montgomery |
| Jul 3 | The Wind in the Willows (1908) author | Kenneth Grahame |
| Jul 3 | Alice's Adventures in Wonderland author | Lewis Carroll |
| Jul 3 | I, Robot / Foundation series author | Isaac Asimov |
| Jul 3 | Moulin Rouge cabaret poster painter | Henri de Toulouse-Lautrec |
| Jul 3 | "Shall I compare thee to a summer's day?" | Shakespeare's Sonnet 18 |

### Founded & Invented
| Jul 3 | Adobe founded | 1982, John Warnock & Charles Geschke |
| Jul 3 | Gucci founded | 1921, Florence (Guccio Gucci) |
| Jul 3 | Chanel founded | 1910, Paris (Coco Chanel) |
| Jul 3 | Michelin founded | 1889, France (Édouard & André Michelin) |
| Jul 3 | First U.S. roller coaster patent (1885) | LaMarcus Adna Thompson |
| Jul 3 | Fender guitars founded (1946) | Leo Fender |

### General Trivia
| Jul 3 | Animals | Koalas sleep up to ~22 hours a day |
| Jul 3 | Animals | A snail can sleep for up to three years |
| Jul 3 | Animals | Kangaroos can't walk backwards |
| Jul 3 | Science | Vantablack absorbs ~99.96% of visible light |
| Jul 3 | Astronomy | Saturn's moon Titan has lakes/rivers of liquid methane |
| Jul 3 | Language | "Nerd" coined by Dr. Seuss in If I Ran the Zoo (1950) |
| Jul 3 | Food | Lobster was once colonial "poverty food" |
| Jul 3 | Body | Humans are the only animals with a true chin |
| Jul 3 | Geography | Challenger Deep (Mariana Trench) = ocean's deepest point ~36,000 ft |
| Jul 3 | Geography | Angel Falls (Venezuela) = world's tallest waterfall ~3,212 ft |
| Jul 3 | Sports | Olympic gold medal is mostly silver (~6g gold required) |

### Songs
| Jul 3 | Bitter Sweet Symphony | The Verve | 1997 |
| Jul 3 | No Diggity | Blackstreet ft. Dr. Dre & Queen Pen | 1996 |
| Jul 3 | Iris | Goo Goo Dolls | 1998 |
| Jul 3 | Hips Don't Lie | Shakira ft. Wyclef Jean | 2006 |
| Jul 3 | How You Remind Me | Nickelback | 2001 |
| Jul 3 | Torn | Natalie Imbruglia | 1997 |

### This Day in History
| Jul 3 | July 3 (Washington takes command of Continental Army 1775; Battle of Gettysburg ends / Pickett's Charge 1863; Idaho becomes 43rd state 1890) | — |
| Jul 3 | National Days: Independence Day observed; National Fried Clam Day; National Eat Your Beans Day; National Compliment Your Mirror Day; Air Conditioning Appreciation Day | — |

### Sports / Current Events
| Jul 3 | Reds | 40-46, 5th NL Central 13.5 GB (Brewers 53-32); last 5 L-L-L-L-W (streak W1); snapped 4-game skid with 7-2 win @ Milwaukee Jul 2; TODAY host Baltimore Orioles 7:10 PM ET |
| Jul 3 | Box Office | Toy Story 5 #1 2nd wknd (Jun 26-28) ~$70.8M, ~$298M domestic; Supergirl $37M open; opening Jul 3-5: Minions & Monsters, Young Washington |
| Jul 3 | Sports | World Cup R32 knockouts: Egypt beat Australia on PKs; Jul 3 Argentina-Cabo Verde (Miami), Colombia-Ghana (KC); R16 begins Jul 4. Wimbledon: 15 seeds out in 4 days, Medvedev (8) upset by Struff, Andreeva (5) out to Krejcikova, Sinner/Djokovic into R3. MLB ASG starters: Ohtani (NL), Ernie Clement (AL), game Jul 14 Philadelphia. NHL FA: Bobrovsky to Toronto, Ovechkin re-signs Washington, Hischier extends NJ. NBA: Ayton to Wizards, signings begin Jul 6 |
| Jul 3 | Deaths | Mignon Dunn (98, Met Opera mezzo-soprano, Jun 28); Vlado Janevski (65, N. Macedonia's first Eurovision act, Jun 28); Ali Ideflawen (69, Algerian Kabyle singer, Jun 28); Antoinette Miggiani (88, Maltese soprano, Jun 29) |
| Jul 3 | Current Events | Record heat dome (185M+ under alerts, DC hit 102°F breaking 1872 record); America's 250th (Semiquincentennial) weekend; Iran begins dayslong funeral for slain supreme leader; Taylor Swift & Travis Kelce donate to 20 charities ahead of wedding |

## July 6, 2026 (v37)

### Capitals
| Jul 6 | Kentucky | Frankfort |
| Jul 6 | North Dakota | Bismarck |
| Jul 6 | Croatia | Zagreb |
| Jul 6 | Latvia | Riga |

### Classic TV
| Jul 6 | The Fugitive (1963-67) | Dr. Richard Kimble | David Janssen |
| Jul 6 | Get Smart (1965-70) | Maxwell Smart / Agent 86 | Don Adams |
| Jul 6 | Sanford and Son (1972-77) | Fred Sanford | Redd Foxx |
| Jul 6 | Barney Miller (1975-82) | Captain Barney Miller | Hal Linden |
| Jul 6 | Dallas (1978-91) | J.R. Ewing | Larry Hagman |
| Jul 6 | Quantum Leap (1989-93) | Dr. Sam Beckett | Scott Bakula |

### Arts & Literature
| Jul 6 | Crime and Punishment / The Brothers Karamazov author | Fyodor Dostoevsky |
| Jul 6 | War and Peace / Anna Karenina author | Leo Tolstoy |
| Jul 6 | The Starry Night painter | Vincent van Gogh |
| Jul 6 | Pride and Prejudice author | Jane Austen |
| Jul 6 | Bolero composer | Maurice Ravel |
| Jul 6 | The Scream painter | Edvard Munch |

### Founded & Invented
| Jul 6 | Netflix founded | 1997, Reed Hastings & Marc Randolph |
| Jul 6 | Starbucks founded | 1971, Seattle (Pike Place) |
| Jul 6 | Airbnb founded | 2008, Chesky/Gebbia/Blecharczyk |
| Jul 6 | First Ferris wheel (1893 Chicago World's Fair) | George W. G. Ferris Jr. |
| Jul 6 | Europe's first movable-type printing press (c.1440) | Johannes Gutenberg |
| Jul 6 | Basketball invented (1891) | James Naismith |

### General Trivia
| Jul 6 | Geography | Sudan has ~2x more ancient pyramids than Egypt (Kingdom of Kush) |
| Jul 6 | Food | Cashews grow on the bottom of the cashew apple fruit |
| Jul 6 | Language | Hawaiian alphabet has only 12 letters (5 vowels, 7 consonants) |
| Jul 6 | Astronomy | Venus (not Mercury) is hottest planet, ~900F, thick CO2 atmosphere |
| Jul 6 | Animals | An ostrich's eye is bigger than its brain |
| Jul 6 | Space | Great Wall of China NOT visible from space with naked eye |
| Jul 6 | Botany | Bananas/avocados are berries; strawberries/raspberries are not |
| Jul 6 | Animals | Sloths can hold breath ~40 min, longer than dolphins |
| Jul 6 | Geography | Antarctica is the world's largest desert (defined by precipitation) |
| Jul 6 | Cards | King of Hearts is the only king with no mustache in a standard deck |
| Jul 6 | History | Napoleon was ~5'6"-5'7" (average for era); "short" was British propaganda |

### Songs
| Jul 6 | Everlong | Foo Fighters | 1997 |
| Jul 6 | Gangsta's Paradise | Coolio ft. L.V. | 1995 |
| Jul 6 | Black | Pearl Jam | 1991 |
| Jul 6 | This Love | Maroon 5 | 2004 |
| Jul 6 | Complicated | Avril Lavigne | 2002 |
| Jul 6 | Since U Been Gone | Kelly Clarkson | 2004 |

### This Day in History
| Jul 6 | July 6 (Continental Congress establishes the dollar as US currency 1785; Pasteur administers rabies vaccine to Joseph Meister 1885; Lennon meets McCartney 1957) | - |
| Jul 6 | National Days: National Fried Chicken Day; National Hand Roll Day; National Air Traffic Control Day; International Kissing Day | - |

### Sports / Current Events
| Jul 6 | Reds | 41-48, 5th NL Central 14.5 GB (Brewers 55-33); last 5 L-W-L-L-W (streak W1); beat Baltimore 3-2 Jul 5; NO GAME today, next host Phillies Tue Jul 7 7:10 PM ET |
| Jul 6 | Box Office | Minions & Monsters #1 franchise-low open $36.4M 3-day/$61.4M 5-day; Toy Story 5 past $366M; Supergirl -77%; opening Jul 10-12: Moana (live-action), Evil Dead Burn |
| Jul 6 | Sports | World Cup: USMNT won group, beat Bosnia 2-0, face Belgium R16 Fri Jul 10 Inglewood; Wimbledon week 2, Eala v Paolini R4; MLB ASG Philly Jul 14, Derby Jul 13 Netflix (Harper 9th/Legend, Freeman 10th, Ohtani 6th); NHL: Flyers 5yr/$90M offer sheet to Leo Carlsson, Bobrovsky to Toronto; NBA signings open Jul 6, champ Knicks add Drummond 1yr/$3.8M, Wiggins ext Miami; NFL camps report Jul 22-28 |
| Jul 6 | Deaths | Victor Willis (74, Village People frontman, co-wrote YMCA, Jun 30); Mike Wallace (historian, Pulitzer-winning Gotham co-author, Jul 5); Antoinette Miggiani (88, Maltese soprano, Jun 29); Fernando Kliche (Uruguayan actor, Jul 3) |
| Jul 6 | Current Events | Trump at NATO summit in Ankara, to meet Zelensky (100+ protesters detained); USMNT World Cup fever, Balogun ban suspended; Super Typhoon Bavi hits N. Mariana Islands; Paul Pelosi hit-and-run in CA |

## July 8, 2026 (v38)

### Capitals
| Jul 8 | California | Sacramento |
| Jul 8 | Minnesota | St. Paul |
| Jul 8 | Ecuador | Quito |
| Jul 8 | Sweden | Stockholm |

### Classic TV
| Jul 8 | The Fall Guy (1981-86) | Colt Seavers | Lee Majors |
| Jul 8 | Simon & Simon (1981-89) | Rick & A.J. Simon | Gerald McRaney & Jameson Parker |
| Jul 8 | Matlock (1986-95) | Ben Matlock | Andy Griffith |
| Jul 8 | Buck Rogers in the 25th Century (1979-81) | Buck Rogers | Gil Gerard |
| Jul 8 | Perfect Strangers (1986-93) | Balki Bartokomous | Bronson Pinchot |
| Jul 8 | Alice (1976-85) | Alice Hyatt | Linda Lavin |

### Arts & Literature
| Jul 8 | Walden / "Civil Disobedience" author | Henry David Thoreau |
| Jul 8 | The Last of the Mohicans author | James Fenimore Cooper |
| Jul 8 | Polish Romantic composer of nocturnes/polonaises | Frédéric Chopin |
| Jul 8 | Olympia / Le Déjeuner sur l'herbe painter | Édouard Manet |
| Jul 8 | "The Charge of the Light Brigade" poet | Alfred, Lord Tennyson |
| Jul 8 | The Color Purple author (1983 Pulitzer) | Alice Walker |

### Founded & Invented
| Jul 8 | Costco first warehouse (Seattle) | 1983 |
| Jul 8 | Barbie doll debut (Ruth Handler / Mattel) | 1959 |
| Jul 8 | Stethoscope invented | René Laennec, 1816 |
| Jul 8 | Windshield wiper patented | Mary Anderson, 1903 |
| Jul 8 | Chocolate chip cookie invented | Ruth Wakefield (Toll House Inn), 1938 |
| Jul 8 | Adidas founded (Adi Dassler, Germany) | 1949 |

### General Trivia
| Jul 8 | Animals | Sea otters hold hands / wrap in kelp while sleeping so they don't drift apart |
| Jul 8 | Geography | Australia (~4,000 km wide) is wider than the Moon (~3,475 km diameter) |
| Jul 8 | Language | "OK" comes from an 1830s Boston newspaper joke abbreviation of "oll korrect" |
| Jul 8 | Animals | A group of flamingos is called a "flamboyance" |
| Jul 8 | Food | In the 1830s ketchup was sold as a patent medicine for indigestion |
| Jul 8 | Biology | A blue whale's heart is ~size of a small car, ~400 lbs |
| Jul 8 | History | A medieval "moment" was a real time unit of ~90 seconds |
| Jul 8 | Art | The Mona Lisa has no visible eyebrows or eyelashes |
| Jul 8 | Science | Ounce for ounce, human bone is stronger than steel |
| Jul 8 | Space | Apollo footprints on the Moon could last millions of years (no wind/water) |

### Songs
| Jul 8 | Livin' la Vida Loca | Ricky Martin | 1999 |
| Jul 8 | Last Resort | Papa Roach | 2000 |
| Jul 8 | Gin and Juice | Snoop Dogg | 1994 |
| Jul 8 | Sugar, We're Goin Down | Fall Out Boy | 2005 |
| Jul 8 | Bad Day | Daniel Powter | 2005 |
| Jul 8 | Only Happy When It Rains | Garbage | 1995 |

### This Day in History
| Jul 8 | July 8 (Vasco da Gama sets sail from Lisbon for India 1497; Wall Street Journal first published 1889; Roswell "flying disc" press release 1947) | - |
| Jul 8 | National Days: SCUD Day; National Chocolate with Almonds Day; National Freezer Pop Day; National Video Game Day | - |

### Sports / Current Events
| Jul 8 | Reds | 41-49, 5th NL Central 16.5 GB (Brewers 58-33); last 5 W-L-L-W-L (streak L1, 3-7 L10); lost 4-1 to Phillies Jul 7; GAME IN PROGRESS today Jul 8 vs Phillies, Reds led 7-4 late (first pitch 7:10 ET) |
| Jul 8 | Box Office | Minions & Monsters #1 franchise-low $36.4M 3-day/$61.4M 5-day; Toy Story 5 past $366M; opening Jul 10-12: Moana (live-action), The Invite (A24, Rogen/Wilde/Cruz/Norton), Evil Dead Burn |
| Jul 8 | Sports | World Cup R16: USMNT ELIMINATED, lost 4-1 to Belgium Jul 6 in Seattle (Tillman goal; De Ketelaere brace; Lukaku late), Belgium to QF; Wimbledon quarterfinals; MLB ASG Philly Jul 14, Derby Jul 13 Netflix, Brewers 58-33 best NL, Royals beat Phillies 15-1; NBA: Celtics trade Jaylen Brown to 76ers, SL debuts Darryn Peterson & Cameron Boozer; NHL: Giroux re-signs Senators (20th yr), Flames sign Simon Nemec 5yr/$36.25M; WNBA All-Star reserves named (Ogwumike), Valkyries surging |
| Jul 8 | Deaths | Beaky/John Dymond (81, of Dave Dee Dozy Beaky Mick & Tich, Jul 5); Lauren Bennett (36, "Party Rock Anthem" vocalist, Jul 6); Gordon S. Wood (92, Pulitzer historian, struck by car, Jul 7) |
| Jul 8 | Current Events | US struck 80+ targets in Iran & reimposed oil sanctions after ship attacks in Strait of Hormuz (Iran vows "crushing response"); Hamas set to cede Gaza to technocratic body; NATO summit in Turkey, Trump praises Erdogan/F-35 talk; July forecast hottest US month |

## August 19, 2026 (v48)

### Reds
| Aug 19 | Record | 60–66, 5th NL Central, 18.0 GB (Brewers 78–48), .476, 7.5 back of last NL WC; L1 streak; 4–6 last 10; last 5 L,L,L,W,L. Split DH with STL Aug 17 (L 1–2, W 6–5), shut out 3–0 Aug 18. Today: Cardinals at Reds 6:40 PM ET. Source: MLB Stats API |

### Box Office
| Aug 19 | #1 | Spider-Man: Brand New Day — $70,711,990 weekend (-51%), $786.5M domestic in 17 days, past $2.02B worldwide (highest-grossing Spider-Man ever). Fun facts used: $47M opening Monday = biggest single Monday in history (beat Black Panther 2018); $1B in six days, 2nd-fastest ever; dir. Destin Daniel Cretton. Behind: The Odyssey $23.6M, The End of Oak Street $21.0M (new), PAW Patrol: The Dino Movie $20.3M (new). Weekend total $163.1M / 61 titles |
| Aug 19 | Coming Aug 21–23 | Mutiny (Jason Statham); Insidious: Out of the Further (Lin Shaye, Brandon Perea); Spa Weekend (Palm Springs comedy); The Magic Faraway Tree (Garfield/Foy/Coughlan) |

### Sports / Deaths / Current Events
| Aug 19 | Sports | Tennis (LOCAL): Cincinnati Open Aug 13–23, Lindner Family Tennis Center, Mason — Mon R32: Zverev d. Atmane 7-6(4) 7-6(6); Rafael Jodar d. Tabilo 6-2 6-1 (3 games lost); Fils upset Lehecka; de Minaur, Cobolli, Mensik, Tommy Paul through; Fonseca withdrew injured; semis Aug 22, final Aug 23. NFL (LOCAL): Bengals host Chicago Bears preseason Wk2 Sat Aug 22, 7:00 PM ET at Paycor. MLB: Brewers 78-48 best record; Rays 75-49 lead AL; Dodgers 11-5 over Rockies Mon w/ 2 Ohtani HRs; AL Central four teams within 5.5. Golf: BMW Championship Aug 20-23 at Bellerive CC, St. Louis (top 50 → top 30). WNBA: Fever offense surging into playoffs (Clark/Mitchell); first-ever Fever trip to Toronto Tempo Aug 18. NASCAR: Joey Logano won Cook Out 400 at Richmond Aug 15 (2nd of 2026). Soccer: Premier League 2026-27 opens Fri Aug 21; Arsenal 3-0 Man City Community Shield Aug 16 |
| Aug 19 | Deaths | O.J. Brigance (56, Ravens/Dolphins LB, first tackle of Super Bowl XXXV, only man to win both a Grey Cup and Super Bowl, ALS complications Aug 17); Laura Cardoso (98, Brazilian actress, ~7 decades, Aug 18); Fulvio Lucisano (98, Italian film producer, Aug 18); Mike Bailey (84, English footballer/manager — Charlton, Wolves, England — dementia complications Aug 17); Vedrana Rudan (76, Croatian journalist/novelist, Aug 18); Abdelaziz Guerda (79, Algerian actor/stage director, Aug 17) |
| Aug 19 | Current Events | Meta child-safety trial opened Aug 18 in Oakland (state AGs allege Facebook/Instagram designed to addict minors). Florida primaries Aug 18 — Angie Nixon, democratic socialist, won the Democratic US Senate primary. US–Iran 60-day MOU expired with no deal; White House won't extend. Oman oil spill now spread across 2,000+ sq km and fouling beaches. Tropical Storm Lala damaged homes on Hawaii's Big Island; flooding across Midwest/Appalachia, heat alerts in the South. Border-wall construction in Big Bend National Park paused pending on-the-ground review |


---

## August 20, 2026 (v49)

### Reds
| Aug 20 | Record | 61–66, 5th NL Central, 17.0 GB (Brewers 78–49), .480, 6.5 back of last NL WC; W1 streak; 5–5 last 10; last 5 (old→new) L,L,W,L,W. Beat STL 5–4 Aug 19 after being shut out 3–0 Aug 18. Today: Cardinals at Reds 12:40 PM ET day game, series finale, then @ ARI. Source: MLB Stats API |

### Box Office
| Aug 20 | #1 | Spider-Man: Brand New Day — $70,711,990 weekend (Aug 14 wknd still current), $786.5M domestic in 17 days, past $2.02B WW. Fun fact used THIS run: Glasgow doubled for NYC; three full city blocks built at Pinewood. (Aug 19 used the Monday record / $1B in six days / Cretton facts — do not reuse.) Behind: The Odyssey $23.6M, End of Oak Street $21.0M, PAW Patrol: Dino Movie $20.3M, Katseye: Wild Hearts $4.0M. Weekend total $163.1M / 63 titles |
| Aug 20 | Coming Aug 21–23 | Mutiny (Statham, cargo ship revenge); Insidious: Out of the Further (Amelia Eve travels into The Further); Spa Weekend (Palm Springs comedy); The Magic Faraway Tree (Garfield/Foy/Coughlan) |

### Sports / Deaths / Current Events
| Aug 20 | Sports | Tennis (LOCAL): Cincinnati Open — top seeds OUT. Sara Bejlek (No. 35) d. world No. 1 Sabalenka 7-6(9-7) 6-4 (first top-10 win); Tommy Paul saved MP and d. top seed Zverev 4-6 7-6(8-6) 6-4; Gauff through 6-3 6-2 over Bouzkova; Alcaraz withdrew (wrist). QFs Aug 20–21, final Aug 23. MLB: Brewers 22–0 over Mariners Aug 18 — tied franchise record for runs, tied modern MLB record for largest shutout margin (Yelich, Hamilton, Bauers, Lara HRs). Golf: BMW Championship Aug 20–23 Bellerive CC St. Louis, $20M purse, no cut, 50 players, top 30 advance; Scheffler leads FedExCup, McIlroy in field; par 70 / 7,448 yds. NFL (LOCAL): Bengals 16–14 over Lions in preseason opener; host Bears Sat Aug 22 7 PM ET; traded No. 10 pick to NYG for DT Dexter Lawrence, signed edge Boye Mafe. WNBA: Lynx first to clinch; FIBA World Cup break early Sept, resume Sept 17, playoffs tip Sept 27. Soccer: Premier League 2026-27 opens Fri Aug 21; Arsenal 3-0 Man City in Community Shield Aug 16 |
| Aug 20 | Deaths | Frank Beard (77, ZZ Top drummer — the one WITHOUT a beard, Aug 18); Hayden Panettiere (36, Claire Bennet on Heroes / Juliette Barnes on Nashville, Aug 16); Tommy John (83, 288-win pitcher, namesake of the elbow surgery Dr. Frank Jobe pioneered on him in 1974, Aug 15); Nikki Ross (52, singer, Aug 14); Prichard Colón (33, Puerto Rican boxer, 2015 brain injury, Aug 13); Christy Knowings (46, Nickelodeon All That, asthma attack, Aug 11); Ben "Cooter" Jones (84, Dukes of Hazzard + two terms in Congress from Georgia, Aug 9); O.J. Brigance (56, only man to win a Grey Cup and a Super Bowl, ALS, Aug 17) |
| Aug 20 | Current Events | Trump: "no talks or conversations" with Tehran, US naval blockade of Iranian ports remains in full force (mines cleared, other shipping passing); threatened to bomb Oman over its Iran/Hormuz shipping deal. Hormuz traffic slowed again Tuesday. 50% tariff increase on Canadian goods paused three days after Carney call. Israeli strikes killed at least seven Palestinians in Gaza. Sanctions imposed on ICC President and Senior Prosecutor. San Diego Padres staffer in ICE custody after Texas airport arrest. Meta child-safety trial (opened Aug 18, Oakland) ongoing |



## July 9, 2026 (v39)

### Capitals
| Jul 9 | France | Paris |
| Jul 9 | Italy | Rome |
| Jul 9 | Germany | Berlin |
| Jul 9 | India | New Delhi |

### Classic TV
| Jul 9 | Cheyenne (1955–63) | Cheyenne Bodie | Clint Walker |
| Jul 9 | Bat Masterson (1958–61) | Bat Masterson | Gene Barry |
| Jul 9 | The Real McCoys (1957–63) | Grandpa Amos McCoy | Walter Brennan |
| Jul 9 | The Time Tunnel (1966–67) | Dr. Tony Newman | James Darren |
| Jul 9 | Peter Gunn (1958–61) | Peter Gunn | Craig Stevens |
| Jul 9 | The Ghost & Mrs. Muir (1968–70) | Carolyn Muir | Hope Lange |

### Arts & Literature
| Jul 9 | "Ozymandias" sonnet poet | Percy Bysshe Shelley |
| Jul 9 | "The Rime of the Ancient Mariner" poet | Samuel Taylor Coleridge |
| Jul 9 | The Carnival of the Animals composer | Camille Saint-Saëns |
| Jul 9 | The Third of May 1808 painter | Francisco Goya |
| Jul 9 | Twenty Thousand Leagues Under the Sea author | Jules Verne |
| Jul 9 | Mrs. Dalloway / To the Lighthouse author | Virginia Woolf |

### Founded & Invented
| Jul 9 | Barbed wire patent (1874) | Joseph Glidden |
| Jul 9 | First practical helicopter (1939) | Igor Sikorsky |
| Jul 9 | First powered vacuum cleaner (1901) | Hubert Cecil Booth |
| Jul 9 | Revolver patent (1836) | Samuel Colt |
| Jul 9 | 7UP first sold | 1929 (Charles Leiper Grigg) |
| Jul 9 | Parking meter (1935) | Carl Magee |

### General Trivia
| Jul 9 | Language | "Q" is the only letter not in any US state name |
| Jul 9 | Botany | Broccoli, cauliflower, kale, cabbage all same species (Brassica oleracea) |
| Jul 9 | Food | "Hawaiian" pizza was invented in Canada (Sam Panopoulos, 1962) |
| Jul 9 | Animals | Bactrian camels have 2 humps; dromedaries 1 (B vs D on their sides) |
| Jul 9 | Body | Teeth are the only body part that can't repair/heal themselves |
| Jul 9 | Body | The groove between nose and upper lip is the "philtrum" |
| Jul 9 | Did You Know | More plastic pink flamingos in the US than real ones in the wild |
| Jul 9 | Space | Buzz Aldrin took Communion on the Moon — first food/drink consumed there |
| Jul 9 | Animals | Pigeons can be trained to tell a Monet from a Picasso |
| Jul 9 | Language | In Italian the "@" symbol is "chiocciola" (snail) |

### Songs
| Jul 9 | Loser | Beck | 1994 |
| Jul 9 | All the Small Things | blink-182 | 1999 |
| Jul 9 | One Week | Barenaked Ladies | 1998 |
| Jul 9 | Steal My Sunshine | Len | 1999 |
| Jul 9 | Flagpole Sitta | Harvey Danger | 1997 |
| Jul 9 | Learn to Fly | Foo Fighters | 1999 |

### This Day in History
| Jul 9 | July 9 (Braddock routed at Battle of the Monongahela 1755; "Rock Around the Clock" first rock #1 on Billboard 1955; Warhol's Campbell's Soup Cans debut at Ferus Gallery 1962) | - |
| Jul 9 | National Days: Argentina Independence Day; National Sugar Cookie Day; Nunavut Day (Canada); Fashion Day | - |

### Sports / Current Events
| Jul 9 | Reds | 42-49, 5th NL Central 15.5 GB (Brewers 58-34); last 5 L-L-W-L-W (streak W1, 3-7 L10); beat Phillies 11-5 Jul 8; GAME TONIGHT vs Phillies series finale 7:10 PM ET |
| Jul 9 | Box Office | Minions & Monsters #1 franchise-low $36.4M 3-day/$61.4M 5-day; Toy Story 5 past $366M; opening Jul 10-12: Moana (live-action), Evil Dead Burn, The Invite (A24) |
| Jul 9 | Sports | World Cup QFs: France-Morocco (Foxborough) & Spain-Belgium (Inglewood) Jul 9-10; final 8 = France, Morocco, Spain, Belgium, Norway, England, Argentina, Switzerland. Wimbledon women's semis today (Gauff v Muchova; Kostyuk v Nosková), men's semis Fri (Sinner-Djokovic, Zverev). MLB ASG Philly Jul 14/Derby Jul 13 Netflix, Brewers 58-34 best NL. NBA: Donovan Mitchell 4yr/$273M ext Cavs, Middleton to Wizards. NHL: Hischier 5yr/$11.7M AAV Devils, Byram to Blackhawks 6yr/$12.5M |
| Jul 9 | Deaths | Gordon S. Wood (92, Pulitzer historian, struck by car, Jul 7); Robbie Francevic (84, NZ racing champ, Jul 6); Slaine Kelly (43, Irish actress, cancer, Jul 5); Lauren Bennett (36, "Party Rock Anthem" vocalist, Jul 6) |
| Jul 9 | Current Events | US-Iran ceasefire in doubt after fresh strikes (Iran fires toward Bahrain/Kuwait/Qatar); Trump-Zelensky at NATO Turkey summit, US to license Ukraine Patriot production; Russia missile/drone barrage kills 22+ Ukraine; Marine Le Pen to run for French presidency despite monitor; Venezuela quake toll past 3,300 |

---

## August 5, 2026 (v40)

### Capitals
| Aug 5 | Malawi | Lilongwe |
| Aug 5 | Nicaragua | Managua |
| Aug 5 | Montenegro | Podgorica |
| Aug 5 | Palau | Ngerulmud |
| Aug 5 | NOTE | All 50 US state capitals now exhausted — future runs should be all-world or reuse oldest states |

### Classic TV
| Aug 5 | Peyton Place (1964–69) | Allison MacKenzie | Mia Farrow |
| Aug 5 | The Courtship of Eddie's Father (1969–72) | Tom Corbett | Bill Bixby |
| Aug 5 | Room 222 (1969–74) | Pete Dixon | Lloyd Haynes |
| Aug 5 | Hardcastle and McCormick (1983–86) | Judge Milton C. Hardcastle | Brian Keith |
| Aug 5 | Silver Spoons (1982–87) | Derek Taylor | Jason Bateman |
| Aug 5 | The Practice (1997–2004) | Bobby Donnell | Dylan McDermott |

### Arts & Literature
| Aug 5 | First Japanese Nobel Literature laureate (1968) | Yasunari Kawabata |
| Aug 5 | The Godfather (1969) author | Mario Puzo |
| Aug 5 | The Fighting Temeraire / Rain, Steam and Speed painter | J.M.W. Turner |
| Aug 5 | "Resurrection" Symphony No. 2 composer | Gustav Mahler |
| Aug 5 | Ficciones / The Aleph author | Jorge Luis Borges |
| Aug 5 | The Little Mermaid statue sculptor (1913) | Edvard Eriksen |

### Founded & Invented
| Aug 5 | First portable fire extinguisher (1818) | George William Manby |
| Aug 5 | Jeep WWII manufacturer | Willys-Overland (Bantam prototype 1940) |
| Aug 5 | Modern pin tumbler lock (1861–65) | Linus Yale Jr. |
| Aug 5 | Hasbro founded | 1923, Hassenfeld Brothers, Providence RI |
| Aug 5 | Whirlpool bath / Jacuzzi (1956) | Candido Jacuzzi |
| Aug 5 | Instant ramen (1958) | Momofuku Ando |

### General Trivia
| Aug 5 | Science | Helium — only element found in space (1868 Sun spectrum) before Earth |
| Aug 5 | Geography | Nauru has no official capital; offices in Yaren district |
| Aug 5 | Food | Ripe cranberries bounce; graded on "bounce boards" |
| Aug 5 | History | Harvard (1636) is older than calculus (1660s–70s) |
| Aug 5 | Sports | Olympic gold medals are mostly silver — ~6g gold plating required |
| Aug 5 | Pop Culture | Mario debuted in Donkey Kong (1981) as carpenter "Jumpman" |
| Aug 5 | Animals | A group of ladybugs is a "loveliness" |
| Aug 5 | Language | "Dord" — ghost word in Webster's 1934–1947 from "D or d" (density) |
| Aug 5 | Space | Enceladus plumes feed Saturn's E ring |
| Aug 5 | Did You Know | Nishiyama Onsen Keiunkan (Japan, 705 AD) — oldest hotel, 52 generations |
| Aug 5 | History | Great Molasses Flood, Boston 1919 — 2.3M gallons, ~35 mph, 21 dead |
| Aug 5 | Science | Human bone ~4x compressive strength of concrete pound for pound |

### Songs
| Aug 5 | Regulate | Warren G feat. Nate Dogg | 1994 |
| Aug 5 | Interstate Love Song | Stone Temple Pilots | 1994 |
| Aug 5 | Breakfast at Tiffany's | Deep Blue Something | 1995 |
| Aug 5 | Fly Away | Lenny Kravitz | 1998 |
| Aug 5 | Meet Virginia | Train | 1998 |
| Aug 5 | Hey Ya! | OutKast | 2003 |

### This Day in History
| Aug 5 | August 5 (Statue of Liberty pedestal cornerstone laid 1884; first electric traffic signal, Cleveland 1914; Marilyn Monroe found dead 1962; Reagan fires 11,000+ PATCO air traffic controllers 1981) | - |
| Aug 5 | National Days: National Oyster Day; National Underwear Day; National Work Like a Dog Day; International Traffic Light Day; National Dash Cam Day | - |

### Sports / Current Events
| Aug 5 | Reds | 54-58, 5th NL Central 15.5 GB (Brewers 70-43); last 5 W-W-L-W-W (streak W2, 6-4 L10); took 3 of 4 from Pirates incl 10-2, beat Athletics 5-4 Aug 4; GAME TONIGHT vs Athletics 6:40 PM ET |
| Aug 5 | Box Office | Spider-Man: Brand New Day #1 with $360.1M — biggest domestic opening ever (passed Endgame $357.1M); records for Thursday previews ($72M) and single day ($168M Fri); The Odyssey $51M/$395M total = biggest overall weekend in history; opening Aug 7-9: Super Troopers 3, Ice Cream Man, One Night Only, The Last House |
| Aug 5 | Sports | NFL camps week 2, HOF Game Aug 6 Cardinals-Panthers; Seahawks defending SB LX champs open vs Patriots Sept 9; Jalon Walker (ATL) feared torn ACL, Coby Bryant (CHI) out 8-10 wks. MLB: Brewers 70-43 best, Dodgers 69-45 (L5), Braves 68-45 (W6), Padres 8-2 L10. Soccer: Messi's first Miami game post-WC, 2-2 draw w/ Columbus; Lewandowski 2 goals in Chicago Fire home debut; Leagues Cup begins. World Cup final recap: Spain 1-0 Argentina, Ferran Torres 106', MetLife, Jul 19. NCAA: preseason Coaches Poll — Ohio State #1 (38/72 firsts), Oregon 2, Georgia 3, Texas 4, Notre Dame 5; AP poll Aug 17. WNBA: trade deadline Aug 2, 15 teams (Portland Fire, Toronto Tempo), FIBA break Aug 31-Sep 16 |
| Aug 5 | Deaths | David Z (78, Grammy producer/engineer — Prince, Fine Young Cannibals, Jonny Lang, Aug 2); Peter Gill (86, Welsh playwright/director, Aug 4); Jimmy Cricket (80, Irish comedian b. James Mulgrew, Aug 3); Andrzej Morozowski (69, Polish TV journalist, Aug 4); Allan Nascimento (34, Brazilian UFC flyweight, Aug 3) |
| Aug 5 | Current Events | Cargo ship hit by projectile off Oman in Strait of Hormuz, crew abandoned ship, one missing; Iran-Oman near deal to reopen strait. Berlin police kill suspect in Pride attack (1 dead, 29 wounded). Jocelyn Benson wins Michigan Dem gubernatorial primary with 84%. Todd Blanche AG nomination back on track (Cornyn, Tillis). Record European heat waves and wildfires; arson arrest in Washington state. Multi-state cyclosporiasis outbreak (AR, IA, MO, NE, NH, NC) |

---

## August 6, 2026 (v41)

### Capitals
| Aug 6 | Uzbekistan | Tashkent |
| Aug 6 | Cote d'Ivoire | Yamoussoukro (official; Abidjan largest city) |
| Aug 6 | Papua New Guinea | Port Moresby |
| Aug 6 | Bosnia and Herzegovina | Sarajevo |

### Classic TV
| Aug 6 | The Virginian (1962-71) | The Virginian | James Drury |
| Aug 6 | Hazel (1961-66) | Hazel Burke | Shirley Booth |
| Aug 6 | Ben Casey (1961-66) | Dr. Ben Casey | Vince Edwards |
| Aug 6 | Vega$ (1978-81) | Dan Tanna | Robert Urich |
| Aug 6 | Bosom Buddies (1980-82) | Kip Wilson | Tom Hanks |
| Aug 6 | thirtysomething (1987-91) | Michael Steadman | Ken Olin |

### Arts & Literature
| Aug 6 | Rebecca (1938) author / "Last night I dreamt I went to Manderley again" | Daphne du Maurier |
| Aug 6 | Whistlejacket / equine portrait painter | George Stubbs |
| Aug 6 | Concerto for Orchestra / Bluebeard's Castle composer | Bela Bartok |
| Aug 6 | "I Wandered Lonely as a Cloud" (daffodils) poet | William Wordsworth |
| Aug 6 | First woman to win Nobel Literature (1909) | Selma Lagerlof (Sweden) |
| Aug 6 | Four-time Pulitzer playwright, Long Day's Journey into Night | Eugene O'Neill |

### Founded & Invented
| Aug 6 | Escalator patent | Jesse Reno, 1892 (Coney Island; Otis trademark) |
| Aug 6 | Rolex founded | Hans Wilsdorf, 1905 London (Geneva 1919) |
| Aug 6 | First ATM | 1967, Barclays Enfield London (John Shepherd-Barron) |
| Aug 6 | First implantable pacemaker | 1958, Rune Elmqvist device / Ake Senning |
| Aug 6 | Oldest registered US distillery | Jack Daniel's, registered 1866 |
| Aug 6 | First US roller coaster | Switchback Railway, 1884, LaMarcus Thompson, Coney Island |

### General Trivia
| Aug 6 | Science | Lightning bolt ~30,000 K — about 5x hotter than the Sun's surface |
| Aug 6 | Geography | Istanbul is the only major city on two continents (Bosphorus) |
| Aug 6 | Food | Carrots were originally purple/white/yellow; orange bred in 17th-c Netherlands |
| Aug 6 | Animals | Octopuses have three hearts and blue (copper-based hemocyanin) blood |
| Aug 6 | Language | "Set" has historically had the most OED definitions of any word |
| Aug 6 | Space | A day on Venus (~243 Earth days) is longer than its year (~225) |
| Aug 6 | History | Oxford University (teaching by 1096) is older than the Aztec Empire (1325) |
| Aug 6 | Sports | Golf balls have 300-500 dimples; dimpled ball flies ~2x farther than smooth |
| Aug 6 | Body | Stomach lining replaces itself every few days so acid doesn't digest it |
| Aug 6 | Did You Know | Wombat droppings are cube-shaped (won't roll off scent-marker rocks) |
| Aug 6 | Pop Culture | "Wilhelm scream" first appeared in Distant Drums (1951) |
| Aug 6 | History | Anglo-Zanzibar War (Aug 27, 1896) — shortest war ever, ~38 minutes |

### Songs
| Aug 6 | Everybody Hurts | R.E.M. | 1992 |
| Aug 6 | Cannonball | The Breeders | 1993 |
| Aug 6 | Doo Wop (That Thing) | Lauryn Hill | 1998 |
| Aug 6 | Chop Suey! | System of a Down | 2001 |
| Aug 6 | Take Me Out | Franz Ferdinand | 2004 |
| Aug 6 | Rehab | Amy Winehouse | 2006 |

### This Day in History
| Aug 6 | August 6 (Hiroshima atomic bomb 1945; Holy Roman Empire dissolved by Francis II 1806; Gertrude Ederle first woman to swim English Channel 1926; Voting Rights Act signed 1965; William Kemmler first electric-chair execution 1890) | - |
| Aug 6 | National Days: National Root Beer Float Day; National IPA Day; Jamaica Independence Day (1962); Bolivia Independence Day (1825); Hiroshima Peace Memorial Day; Wiggle Your Toes Day | - |

### Sports / Current Events
| Aug 6 | Reds | 55-58, 5th NL Central 15.5 GB (Brewers 71-43); last 5 W-L-W-W-W (streak W3, 7-3 L10); beat Athletics 3-2 Aug 5 and 5-4 Aug 4; GAME TODAY vs Athletics 12:40 PM ET at GABP (matinee, sweep on the line). Source: MLB Stats API |
| Aug 6 | Box Office | Spider-Man: Brand New Day still #1 — $360.1M opening (biggest domestic opening ever), ~$1.155B worldwide in 7 days ($449M dom / $706M intl); $1B in 6 days (2nd fastest); highest-grossing film of 2026 in 7 days; fastest to $400M domestic (4 days); $42M Tuesday = biggest US Tuesday ever. Opening Aug 7-9: Super Troopers 3, Ice Cream Man, One Night Only, The Last House (Tony limited) |
| Aug 6 | Sports | NFL preseason opens TONIGHT — HOF Game Panthers vs Cardinals 8 PM ET NBC/Peacock, Canton; HOF Class 2026 = Brees, Roger Craig, Fitzgerald, Kuechly, Vinatieri; Carson Beck starts for ARI under 1st-yr HC Mike LaFleur. MLB deadline Aug 3: Skubal to Dodgers, Rutschman to Red Sox, Holmes to Cubs, Arraez to Phillies, May to Brewers, Ramos to Yankees, Ward to Mariners; Orioles sold. NHL: Macklin Celebrini 5-yr ext w/ Sharks $18.8M AAV — highest AAV in NHL history at 20. NBA: Draymond Green back to GSW 1yr/$27.7M; Kuminga market cold; DeRozan drawing WAS/MIA/DEN/CLE interest. Soccer: Leagues Cup underway Aug 4-Sep 6 (18 MLS + 18 Liga MX). NCAA: preseason Coaches Poll Aug 4, Ohio State #1; AP poll Aug 17 |
| Aug 6 | Deaths | Vincent Pastore (80, "Big Pussy" on The Sopranos, Aug 1); Dory Funk Jr. (85, NWA world champion/wrestling trainer, Aug 4); Daniele Amati (94, Italian theoretical physicist, Aug 4); Liam O'Neill (70, GAA president 2012-15, Aug 4); Jakob Butturff (32, pro bowler, Jul 31) |
| Aug 6 | Current Events | Abdul El-Sayed wins Michigan Dem SENATE primary (progressive marquee win); Jocelyn Benson takes gubernatorial primary ~84%; thin margins leave Dem direction unsettled. Indiana Medicaid enrollment falling sharply under new federal eligibility rules. Strait of Hormuz shipping still disrupted after cargo ship struck off Oman; Iran-Oman reopening talks. Record European heat waves and wildfires continue |

---

## August 7, 2026 (v42)

### Capitals
| Week | Question | Answer |
|------|----------|--------|
| Aug 7 | Ghana | Accra |
| Aug 7 | Slovakia | Bratislava |
| Aug 7 | Paraguay | Asunción |
| Aug 7 | Turkmenistan | Ashgabat |

### Classic TV
| Week | Show | Character | Actor |
|------|------|-----------|-------|
| Aug 7 | The Beverly Hillbillies | Jed Clampett | Buddy Ebsen |
| Aug 7 | Green Acres | Oliver Wendell Douglas | Eddie Albert |
| Aug 7 | The Rockford Files | Jim Rockford | James Garner |
| Aug 7 | The Twilight Zone | host/creator | Rod Serling |
| Aug 7 | Newhart | Dick Loudon | Bob Newhart |
| Aug 7 | Magnum, P.I. | Thomas Magnum | Tom Selleck |

### Arts & Literature
| Week | Question | Answer |
|------|----------|--------|
| Aug 7 | Novel opening "Call me Ishmael" | Moby-Dick — Herman Melville |
| Aug 7 | Brontë sister who wrote Wuthering Heights | Emily Brontë |
| Aug 7 | Painter of The Persistence of Memory (1931) | Salvador Dalí |
| Aug 7 | Composer of The Nutcracker / 1812 Overture | Tchaikovsky |
| Aug 7 | Author of "The Raven" (1845) | Edgar Allan Poe |
| Aug 7 | 1961 Pulitzer, To Kill a Mockingbird | Harper Lee |

### Founded & Invented
| Week | Question | Answer |
|------|----------|--------|
| Aug 7 | Year LEGO founded | 1932 — Ole Kirk Christiansen, Billund |
| Aug 7 | Inventor of modern ballpoint pen | László Bíró (1938) |
| Aug 7 | Year Ray Kroc franchised McDonald's | 1955 (original stand 1940) |
| Aug 7 | Inventor of modern zipper | Gideon Sundback (1913) |
| Aug 7 | Year Harley-Davidson founded | 1903, Milwaukee |
| Aug 7 | Inventor of bubble gum | Walter Diemer, Fleer, 1928 (Dubble Bubble) |

### General Trivia
| Week | Topic | Fact |
|------|-------|------|
| Aug 7 | Animals | Crows = "murder", ravens = "unkindness" |
| Aug 7 | Food/Botany | Peanuts are legumes, grow underground |
| Aug 7 | Geography | Maine is US state closest to Africa |
| Aug 7 | History/Language | Baker's dozen = 13, medieval short-weight penalties |
| Aug 7 | History | Great Pyramid only surviving Ancient Wonder |
| Aug 7 | Science | Sound travels ~4x faster in water than air |
| Aug 7 | Sports | Wimbledon only Grand Slam still on grass |
| Aug 7 | Animals | Butterflies taste with their feet |
| Aug 7 | Math/Science | Shannon number ~10^120 chess games > atoms in universe |
| Aug 7 | Language | "Salary" from Latin salarium, tied to salt |
| Aug 7 | Geography | Iceland has no mosquitoes |
| Aug 7 | Language/Food | Single strand of spaghetti = "spaghetto" |

### Songs
| Aug 7 | Mr. Jones | Counting Crows | 1993 |
| Aug 7 | Song 2 | Blur | 1997 |
| Aug 7 | Semi-Charmed Life | Third Eye Blind | 1997 |
| Aug 7 | You Get What You Give | New Radicals | 1998 |
| Aug 7 | Kryptonite | 3 Doors Down | 2000 |
| Aug 7 | Float On | Modest Mouse | 2004 |

### This Day in History
| Aug 7 | August 7 (Washington creates Badge of Military Merit/Purple Heart 1782; Marines land on Guadalcanal 1942; Gulf of Tonkin Resolution 1964; Philippe Petit tightrope walk between Twin Towers 1974; US embassy bombings Nairobi & Dar es Salaam 1998) | - |
| Aug 7 | National Days: International Beer Day; National Lighthouse Day; National Sea Serpent Day; Beach Party Day; Braham Pie Day; Sturgis Motorcycle Rally begins | - |

### Sports / Current Events
| Aug 7 | Reds | 56-58, 4th NL Central 15.5 GB (Brewers 72-43); last 5 L-W-W-W-W (streak W4, 7-3 L10); swept Athletics 5-4, 3-2, 6-5; GAME TODAY @ Nationals 6:45 PM ET |
| Aug 7 | Box Office | Spider-Man: Brand New Day #1 — $360.1M opening (biggest ever, passed Endgame $357.1M), $407.2M through 4 days (fastest to $400M), >$1B worldwide; The Odyssey 2nd, past $405M. Opening Aug 7-9: Super Troopers 3, One Night Only, Ice Cream Man, The Last House |
| Aug 7 | Sports | NFL: HOF Game Aug 6 Cardinals-Panthers, Mike LaFleur HC debut, rookie Carson Beck started, Bryce Young rested; Colts-Jonathan Taylor 2yr/$44M ext; enshrinement Aug 8. MLB deadline (Aug 3): Skubal→Dodgers, Rutschman→Red Sox, Arraez+Raley→Phillies, Gausman+Holmes→Cubs, May→Brewers, Kremer→Twins. Standings: Brewers 72-43 best, Braves 70-45 W8, Dodgers 69-46 L6. WNBA: Sparks over first-place Lynx (49-34 2nd half), Rivals Week Aug 8-14. Soccer: Leagues Cup Aug 4-Sep 6, 36 clubs; Aug 6 América-San Diego at Azteca, Cruz Azul-Philadelphia |
| Aug 7 | Deaths | Robby Albarado (52, jockey, 2007 Preakness on Curlin, after heart surgery); Didier Decoin (81, French novelist, 1977 Prix Goncourt, Aug 5); Peter Lai (76, HK lyricist/actor, Aug 5); David Owori (27, Ugandan footballer SC Villa, Aug 5) |
| Aug 7 | Current Events | Trump says he called off large-scale Iran strike; 20M+ Shia pilgrims at Arbaeen in Karbala; NM judge orders Meta to pay additional $567M in child-safety suit; Britain drought/food shortage warnings, heat alerts 8 regions >30C; school shooting Nonthaburi province Thailand Aug 7; Fauci contempt-of-Congress resolution advances out of Senate committee on party lines |

---

## August 10, 2026 (v43)

### Capitals
| Week | Question | Answer |
|------|----------|--------|
| Aug 10 | Kazakhstan | Astana (Nur-Sultan 2019-22, then back to Astana) |
| Aug 10 | Bolivia | Sucre (constitutional capital; La Paz = seat of government) |
| Aug 10 | Tanzania | Dodoma (not Dar es Salaam) |
| Aug 10 | Denmark | Copenhagen |

### Classic TV
| Week | Show | Character | Actor |
|------|------|-----------|-------|
| Aug 10 | Gunsmoke (1955-75) | Marshal Matt Dillon | James Arness |
| Aug 10 | The Man from U.N.C.L.E. (1964-68) | Napoleon Solo | Robert Vaughn |
| Aug 10 | WKRP in Cincinnati (1978-82) | Dr. Johnny Fever | Howard Hesseman |
| Aug 10 | Kojak (1973-78) | Lt. Theo Kojak | Telly Savalas |
| Aug 10 | Dynasty (1981-89) | Alexis Colby | Joan Collins |
| Aug 10 | Northern Exposure (1990-95) | Dr. Joel Fleischman | Rob Morrow |

### Arts & Literature
| Week | Question | Answer |
|------|----------|--------|
| Aug 10 | Novel opening "the clocks were striking thirteen" | 1984 - George Orwell |
| Aug 10 | Painter of Nighthawks (1942) | Edward Hopper |
| Aug 10 | Composer of Rhapsody in Blue (1924) | George Gershwin |
| Aug 10 | Author of Things Fall Apart (1958) | Chinua Achebe |
| Aug 10 | Playwright, Death of a Salesman (1949 Pulitzer) | Arthur Miller |
| Aug 10 | Poet, "Because I could not stop for Death" | Emily Dickinson |

### Founded & Invented
| Week | Question | Answer |
|------|----------|--------|
| Aug 10 | Play-Doh original product / company | Wallpaper cleaner, Kutol Products of Cincinnati (toy relaunch 1956) |
| Aug 10 | Kevlar inventor / year | Stephanie Kwolek, DuPont, 1965 |
| Aug 10 | Microwave oven inventor | Percy Spencer, Raytheon, 1945 (melted candy bar near magnetron) |
| Aug 10 | Nintendo founded / original product | 1889, Kyoto - hanafuda playing cards |
| Aug 10 | Bubble Wrap original intended product (1957) | Textured wallpaper |
| Aug 10 | First item scanned with a UPC barcode | Wrigley's Juicy Fruit 10-pack, Troy OH, 1974 |

### General Trivia
| Week | Topic | Fact |
|------|-------|------|
| Aug 10 | Food | Honey never spoils - 3,000-yr-old edible honey found in Egyptian tombs |
| Aug 10 | Geography | Canada has more lakes (~2 million) than the rest of the world combined |
| Aug 10 | Animals | A group of porcupines is a "prickle" |
| Aug 10 | Food | Worcestershire sauce is made with fermented anchovies |
| Aug 10 | History | France's last guillotine execution (1977) - same year as Star Wars |
| Aug 10 | Biology | Humans share ~60% of their DNA with bananas |
| Aug 10 | Space | Saturn is less dense than water - it would float |
| Aug 10 | Sports | Olympic torch relay isn't ancient - invented for the 1936 Berlin Games |
| Aug 10 | Language | "Muscle" from Latin musculus = "little mouse" |
| Aug 10 | Pop Culture | James Earl Jones uncredited as Darth Vader's voice in 1977 Star Wars |
| Aug 10 | Did You Know | Scotland's national animal is the unicorn |
| Aug 10 | Travel | Shortest scheduled flight: Westray to Papa Westray, Scotland (~90 sec) |

### Songs
| Aug 10 | Under the Bridge | Red Hot Chili Peppers | 1991 |
| Aug 10 | Waterfalls | TLC | 1995 |
| Aug 10 | 1979 | The Smashing Pumpkins | 1996 |
| Aug 10 | Smooth | Santana feat. Rob Thomas | 1999 |
| Aug 10 | The Middle | Jimmy Eat World | 2001 |
| Aug 10 | Crazy | Gnarls Barkley | 2006 |

### This Day in History
| Aug 10 | August 10 (Louvre opens to the public 1793; first electric guitar patent #2,089,171 to George Beauchamp for the Rickenbacker "Frying Pan" 1937; The Wizard of Oz world premiere in Green Bay WI 1939; Pete Rose passes Stan Musial for the NL career hits record with #3,631 in 1981) | - |
| Aug 10 | National Days: National S'mores Day; National Lazy Day; World Lion Day; National Spoil Your Dog Day; Duran Duran Appreciation Day; Ecuador Independence Day (1809) | - |

### Sports / Current Events
| Aug 10 | Reds | 56-61, 5th NL Central 17.5 GB (Brewers 74-44); last 5 W-W-L-L-L (streak L3, 6-4 L10); swept Athletics at home 5-4, 3-2, 6-5 then swept BY Nationals 3-5, 2-8, 1-7; NO GAME TODAY (off day), next @ White Sox Tue Aug 11 7:40 PM ET. Source: MLB Stats API |
| Aug 10 | Box Office | Spider-Man: Brand New Day #1 2nd weekend $145M (-60%), $655M domestic in 10 days (biggest 10-day ever), ~$1.67B worldwide; first film to clear $500M domestic in opening week (7 days); 3rd-biggest 2nd weekend ever. Tom Holland asked Sony to delay 6 months to shoot Nolan's The Odyssey first - Odyssey finished #2 this weekend ($31.5M, $461M dom, Nolan's biggest ever). Top 5: One Night Only $5.7M, Super Troopers 3 $4.0M, Toy Story 5 $3.9M. Opening Aug 14-16: The End of Oak Street, PAW Patrol: The Dino Movie, The Brink of War, The Wrong Girls |
| Aug 10 | Sports | NFL: HOF Game Aug 6 Panthers 33-Cardinals 30 on last play; Class of 2026 enshrined Aug 8 (Brees, Fitzgerald, Kuechly, Roger Craig, Vinatieri); Jalon Walker (ATL) torn ACL out for season, Nic Scourton (CAR) out too; preseason Wk1 opens Aug 13. MLB: Brewers 74-44 best, Braves 71-47, Rays 71-46, Dodgers 70-48; Gerrit Cole 1,000th K as a Yankee Aug 8 (fastest Yankee, 139 games). Soccer: Leagues Cup MD2 MLS 12 wins-Liga MX 6, FC Cincinnati beat Pumas 2-0, Messi becomes Leagues Cup all-time top scorer (14) Aug 5, Monterrey beat Miami 2-1 Aug 8, QFs Aug 25-27. Golf: Michael Brennan wins Wyndham Championship Aug 9 ($1.53M), FedExCup playoffs start Aug 13 TPC Southwind. Tennis: National Bank Open Montreal/Toronto, Fonseca upsets Ruud; Cincinnati Open Aug 13-23. WNBA: Lynx 27-7 best, Liberty 111-71 over Aces Aug 9, Mystics 7 straight, Storm 6-28 eliminated. NHL: Penguins sign Ville Koivunen 8yr/$32M. NCAA: Coaches Poll Aug 4 Ohio State #1 (38/72 firsts), AP poll Aug 17 |
| Aug 10 | Deaths | Don Nelson (86, HOF coach, 2nd-winningest in NBA history, 5 titles as a Celtics player, Aug 9); Ben Jones (84, "Cooter" on The Dukes of Hazzard, 2-term GA congressman, Aug 9); Jorge Messi (68, Lionel Messi's father/agent, Aug 8); Violet Hensley (109, Arkansas "Whittlin' Fiddler," Aug 7); Dory Funk Jr. (85, NWA world champion, Aug 4); Robby Albarado (52, 2x Preakness-winning jockey, Aug 4) |
| Aug 10 | Current Events | Iran published conditions Aug 8 to reopen Strait of Hormuz (end war, lift counterblockade/sanctions, release frozen assets, Iranian control + tolls); Brent ~$84.39. Houthi drones hit Saudi Aramco Jazan refinery Aug 9. Spokane WA wildfires: 7,000+ acres, 600-700 structures, ~60,000 evacuated; BC declared state of emergency Aug 8. Michigan Senate primary Aug 4: Abdul El-Sayed narrowly beat Haley Stevens. Trump signed 15% polysilicon tariff + price floors Aug 6 (effective Dec 4). Measles at 35-year high, ~2,300-2,450 US cases, most since 1991. Cuba's 6th nationwide blackout of 2026, ~10M without power |

---

## August 11, 2026 (v44)

### Capitals
| Week | Question | Answer |
|------|----------|--------|
| Aug 11 | Uruguay | Montevideo |
| Aug 11 | Senegal | Dakar |
| Aug 11 | Mongolia | Ulaanbaatar |
| Aug 11 | Sri Lanka | Sri Jayawardenepura Kotte (Colombo = largest city / commercial capital) |

### Classic TV
| Week | Show | Character | Actor |
|------|------|-----------|-------|
| Aug 11 | Bonanza (1959-73) | Ben Cartwright | Lorne Greene |
| Aug 11 | Hawaii Five-O (1968-80) | Det. Capt. Steve McGarrett | Jack Lord |
| Aug 11 | The Odd Couple (1970-75) | Felix Unger | Tony Randall |
| Aug 11 | Hill Street Blues (1981-87) | Capt. Frank Furillo | Daniel J. Travanti |
| Aug 11 | The Golden Girls (1985-92) | Blanche Devereaux | Rue McClanahan |
| Aug 11 | Star Trek: The Next Generation (1987-94) | Capt. Jean-Luc Picard | Patrick Stewart |

### Arts & Literature
| Week | Question | Answer |
|------|----------|--------|
| Aug 11 | Les Miserables / The Hunchback of Notre-Dame author | Victor Hugo |
| Aug 11 | Brave New World (1932) author | Aldous Huxley |
| Aug 11 | Invisible Man (1952) author | Ralph Ellison |
| Aug 11 | Impression, Sunrise (1872) painter - named Impressionism | Claude Monet |
| Aug 11 | Peter and the Wolf (1936) composer | Sergei Prokofiev |
| Aug 11 | First songwriter to win Nobel Literature (2016) | Bob Dylan |

### Founded & Invented
| Week | Question | Answer |
|------|----------|--------|
| Aug 11 | WD-40 - what "40" means | 40th formula; "Water Displacement, 40th attempt," Rocket Chemical Co. San Diego 1953, for the Atlas missile |
| Aug 11 | Band-Aid inventor | Earle Dickson, 1920, Johnson & Johnson - for his accident-prone wife Josephine |
| Aug 11 | Modern air conditioning inventor / purpose | Willis Carrier, 1902 - humidity control at a Brooklyn printing plant, not comfort |
| Aug 11 | Frisbee origin | Frisbie Pie Company tins; Wham-O "Pluto Platter" 1957, renamed Frisbee 1958 |
| Aug 11 | Origin of the name "Crayola" | French craie (chalk) + oleaginous (oily); Alice Binney, 1903, Binney & Smith |
| Aug 11 | First US fast-food hamburger chain | White Castle, 1921, Wichita KS (white porcelain/steel to fight ground-beef stigma) |

### General Trivia
| Week | Topic | Fact |
|------|-------|------|
| Aug 11 | History (Local) | Roebling Suspension Bridge (Cincinnati, 1866) longest suspension bridge in the world at 1,057 ft; Roebling then built the Brooklyn Bridge |
| Aug 11 | Geography | ~80% of Nevada is federally owned land - highest share of any state |
| Aug 11 | Architecture | Pentagon has ~2x the bathrooms it needs - built 1941 in segregated Virginia, FDR ordered they never be used that way |
| Aug 11 | Language | "Big Ben" is the bell, not the tower; tower renamed Elizabeth Tower in 2012 (was just the Clock Tower) |
| Aug 11 | Animals | Narwhal "tusk" is a canine tooth spiraling through the upper lip, up to 10 ft, full of nerve endings |
| Aug 11 | Space | Olympus Mons (Mars) ~3x the height of Everest, base about the size of Arizona |
| Aug 11 | Science | Roman concrete gets STRONGER in seawater - seawater + volcanic ash grows interlocking crystals |
| Aug 11 | Food | A Twinkie's real shelf life is ~45 days, not decades |
| Aug 11 | Sports | A regulation MLB baseball has exactly 108 double stitches, still hand-sewn |
| Aug 11 | Business | Nike paid student Carolyn Davidson $35 for the Swoosh in 1971 |
| Aug 11 | Tech | "Wi-Fi" doesn't stand for anything - branding-firm name; "Wireless Fidelity" was a dropped slogan |
| Aug 11 | Did You Know | More public libraries in the US (~17,000 outlets) than McDonald's restaurants (~13,500) |

### Songs
| Aug 11 | Been Caught Stealing | Jane's Addiction | 1990 |
| Aug 11 | Runaway Train | Soul Asylum | 1993 |
| Aug 11 | Tubthumping | Chumbawamba | 1997 |
| Aug 11 | I Want It That Way | Backstreet Boys | 1999 |
| Aug 11 | Stacy's Mom | Fountains of Wayne | 2003 |
| Aug 11 | Use Somebody | Kings of Leon | 2008 |

### This Day in History
| Aug 11 | August 11 (DJ Kool Herc's back-to-school party at 1520 Sedgwick Ave, Bronx 1973 - birth of hip-hop; Watts riots begin in LA 1965, 34 dead over six days; Mall of America opens in Bloomington MN 1992) | - |
| Aug 11 | National Days: Hip Hop Day; National Son and Daughter Day; National Presidential Joke Day; Play in the Sand Day; National Raspberry Bombe Day; Global Kinetic Sand Day; National Fufu Day; Chad Independence Day (1960) | - |

### Sports / Current Events
| Aug 11 | Reds | 56-61 (.479), 5th NL Central 17.0 GB (Brewers 74-45); last 5 W-W-L-L-L (streak L3, 6-4 L10); swept Athletics at home then swept BY Nationals 3-5, 2-8, 1-7; off day Aug 10; TODAY @ Chicago White Sox 7:40 PM ET. Source: MLB Stats API |
| Aug 11 | Box Office | Spider-Man: Brand New Day #1 2nd weekend $145M (-60%), $655M domestic in 10 days, ~$1.67B WW. NEW ANGLE USED: $1B worldwide in 6 days (2nd-fastest ever, behind Endgame's 5); biggest domestic opening weekend ever $360M; biggest single Monday ever $46M; highest-grossing 2026 film in 7 days. Top 5: Odyssey $31.5M ($461M dom, Nolan's biggest), One Night Only $5.7M, Super Troopers 3 $4.0M, Toy Story 5 $3.9M. Opening Aug 14-16: The End of Oak Street, The Brink of War, PAW Patrol: The Dino Movie, Six: The Musical Live! |
| Aug 11 | Sports | WNBA: Kayla McBride 10 threes (WNBA single-game record) + career-high 43, Lynx 103-90 over Wings Aug 9; Lynx franchise-record 18 threes, first team to clinch playoff spot, won 12 of 13. MLB: Max Scherzer passed Walter Johnson for 10th all-time in Ks (3,516) vs PHI Aug 8; Brewers 74-45 best, Cubs 69-50. NFL: Aug 10 injuries - Cade Mays (DET, fractured hand), Isiah Pacheco (DET, torn MCL), Laremy Tunsil (WAS, torn triceps); Teddy Bridgewater retires again; joint practices start Aug 11 (DAL-LAR, IND-NE, TB-NYJ); preseason Wk1 Aug 13. Soccer: FC Cincinnati beat Pachuca 3-1 Aug 4 and Pumas 2-0 Aug 7, vs Atlas Aug 11; Leagues Cup Aug 4-Sep 6, QFs Aug 25-27. Golf: FedExCup playoffs open Aug 13, FedEx St. Jude at TPC Southwind, 69 players (Berger WD), Scheffler #1 and +500 favorite, top 50 advance. Tennis: Cincinnati Open Aug 13-23, Sabalenka top women's seed, Zverev/Djokovic/Auger-Aliassime/Medvedev on men's side. NHL: Koivunen 8yr/$32M PIT, Grebenkin 2yr/$2.2M PHI, Bedard 5yr/$15M AAV CHI. NCAA: Coaches Poll Ohio State #1, AP poll Aug 17 |
| Aug 11 | Deaths | Don Nelson (86, HOF coach, 2nd-winningest NBA, 1,335-1,063 over 31 seasons, 5 titles as a Celtics player, invented the point forward, Aug 9 in Frisco TX after a stroke); Ben Jones (84, "Cooter" on The Dukes of Hazzard, 2-term GA congressman, heart attack Aug 9); Jorge Messi (68, Lionel Messi's father/agent, Aug 8); Violet Hensley (109, Arkansas "Whittlin' Fiddler," ~80 handmade violins, Aug 7); Tommy Detamore (70, Texas steel guitarist/producer, Aug 5); Robby Albarado (52, jockey, 5,000+ wins, 2x Preakness incl. Curlin 2007, Aug 4) |
| Aug 11 | Current Events | COLOMBIA EARTHQUAKE Aug 10: M7.4 in western Colombia, strongest recorded this century there; at least 132 dead / 570 injured (Cali 85, Pereira 66; damage in Quibdo, Manizales); state of national disaster. Todd Blanche confirmed US Attorney General 50-49 in an overnight Senate vote Aug 8 (Collins & Murkowski the only GOP no votes; Cassidy decisive). Federal court: no White House ballroom without Congressional approval. Netanyahu says Israel "rejects" the US-backed Board of Peace Gaza disarmament roadmap. Iran near a final pact with Oman to reopen Strait of Hormuz; Houthis hit a Saudi Aramco refinery. Abelardo de la Espriella sworn in as Colombia's president. Ukrainian drone attack killed at least 13 in Russia. Monsoon flooding in India, Brahmaputra over its banks |

---

## August 12, 2026 (v45)

### Capitals
| Week | Question | Answer |
|------|----------|--------|
| Aug 12 | Morocco | Rabat (not Casablanca) |
| Aug 12 | Nigeria | Abuja (moved from Lagos 1991) |
| Aug 12 | Myanmar | Naypyidaw (purpose-built; moved from Yangon 2005) |
| Aug 12 | Croatia | Zagreb |

### Classic TV
| Week | Show | Character | Actor |
|------|------|-----------|-------|
| Aug 12 | Get Smart (1965-70) | Maxwell Smart | Don Adams |
| Aug 12 | The Fugitive (1963-67) | Dr. Richard Kimble | David Janssen |
| Aug 12 | Lost in Space (1965-68) | Dr. Zachary Smith | Jonathan Harris |
| Aug 12 | Barney Miller (1975-82) | Capt. Barney Miller | Hal Linden |
| Aug 12 | Dallas (1978-91) | J.R. Ewing | Larry Hagman |
| Aug 12 | Quantum Leap (1989-93) | Dr. Sam Beckett | Scott Bakula |

### Arts & Literature
| Week | Question | Answer |
|------|----------|--------|
| Aug 12 | "It is a truth universally acknowledged..." opener | Pride and Prejudice (1813) - Jane Austen |
| Aug 12 | Painter of American Gothic (1930) | Grant Wood |
| Aug 12 | Composer of Bolero (1928) | Maurice Ravel |
| Aug 12 | Author of Catch-22 (1961) | Joseph Heller |
| Aug 12 | Poet of "Ozymandias" (1818) | Percy Bysshe Shelley |
| Aug 12 | One Hundred Years of Solitude (1967); Nobel 1982 | Gabriel Garcia Marquez |

### Founded & Invented
| Week | Question | Answer |
|------|----------|--------|
| Aug 12 | Velcro inventor / inspiration | George de Mestral, 1941 (patented 1955) - burdock burrs on his dog; velours + crochet |
| Aug 12 | Riveted blue jeans patent 1873 | Jacob Davis (Reno tailor) & Levi Strauss |
| Aug 12 | Microsoft founded where/when | Albuquerque NM, 1975 (Gates & Allen, near Altair maker MITS) |
| Aug 12 | Super Glue accidental discovery | Harry Coover, 1942 - trying to make clear plastic gun sights; sold 1958 |
| Aug 12 | Slinky inventor | Richard James, 1943, naval engineer; wife Betty named it |
| Aug 12 | What IKEA stands for | Ingvar Kamprad, Elmtaryd (farm), Agunnaryd (village); founded 1943 at age 17 |

### General Trivia
| Week | Topic | Fact |
|------|-------|------|
| Aug 12 | Astronomy | Neptune (discovered 1846) completed its first full orbit only in 2011 - 165-yr year |
| Aug 12 | Animals | A sloth can take up to a month to digest a single leaf |
| Aug 12 | Geography | Mauna Kea measured from the seafloor (~33,500 ft) is taller than Everest (29,032 above sea level) |
| Aug 12 | Food | Vanilla = 2nd-most-expensive spice after saffron; hand-pollinated outside Mexico |
| Aug 12 | History | Roman laundries used stale urine (ammonia); Vespasian taxed it - "pecunia non olet" |
| Aug 12 | Language | Longest dictionary word: pneumonoultramicroscopicsilicovolcanoconiosis (45 letters), coined 1935 |
| Aug 12 | Biology | Slightly more bacterial cells than human cells in the body (~1.3:1) |
| Aug 12 | Sports | First basketball hoops were actual peach baskets; bottoms not cut out until ~1900 |
| Aug 12 | Space | Apollo footprints on the Moon could last millions of years - no wind or water |
| Aug 12 | Business | Michelin Guide created by a tire company (1900) to encourage more driving |
| Aug 12 | Pop Culture | Star Trek's transporter exists because landing the Enterprise every episode was too expensive to film |
| Aug 12 | Science | Bananas are slightly radioactive (potassium-40) - the "banana equivalent dose" |

### Songs
| Week | Song | Artist | Year |
|------|------|--------|------|
| Aug 12 | Enter Sandman | Metallica | 1991 |
| Aug 12 | Loser | Beck | 1994 |
| Aug 12 | Wonderwall | Oasis | 1995 |
| Aug 12 | Torn | Natalie Imbruglia | 1997 |
| Aug 12 | Yeah! | Usher feat. Lil Jon & Ludacris | 2004 |
| Aug 12 | Chasing Cars | Snow Patrol | 2006 |

### This Day in History
| Week | Date Used | Events |
|------|-----------|--------|
| Aug 12 | August 12 (IBM PC model 5150 goes on sale 1981 - 45th anniversary; Susan Hendrickson discovers "Sue" the T. rex in South Dakota 1990; Hawaii formally annexed by the US at Iolani Palace 1898 + Spanish-American War armistice protocol same day) | - |
| Aug 12 | National Days: National Vinyl Record Day; World Elephant Day; International Youth Day (UN); National Middle Child Day; National Sewing Machine Day; IBM PC Day; Baseball Fans Day; National Julienne Fries Day; National Gooey Butter Cake Day | - |

### Sports / Current Events
| Week | Topic | Detail |
|------|-------|--------|
| Aug 12 | Reds | 57-61 (.483), 4th NL Central, 16.0 GB (Brewers 74-46); last 5 W-L-L-L-W (streak W1, 6-4 L10); beat White Sox 5-4 in 10 Aug 11 (De La Cruz sac fly scored McLain; Stephenson tying bases-loaded single in 8th; Pagan 14th save); TODAY @ Chicago White Sox 7:40 PM ET. Source: MLB Stats API |
| Aug 12 | Box Office | Spider-Man: Brand New Day #1. NEW ANGLE USED: final 2nd-weekend actuals $144.2M (-60%), 3rd-biggest 2nd weekend ever; $654.3M domestic; ~$1.67B WW; $225M production budget recouped in ~2 days ($72M previews + $168M Friday). Odyssey $31.7M ($460M+ dom, Nolan's biggest); One Night Only $5.5M. Opening Aug 14-16: The End of Oak Street (David Robert Mitchell, WB, $30-45M tracking), PAW Patrol: The Dino Movie (Cal Brunker, $14-19M), The Brink of War (Angel, Jeff Daniels as Reagan / J.K. Simmons as Gorbachev, ~$4.5M), The Wrong Girls |
| Aug 12 | Sports | Tennis: Cincinnati Open main draw starts Aug 13 (Mason OH), runs to Aug 23; draw ceremony Aug 11; 9 top-10 players, 10 Grand Slam champs; Serena & Venus Williams reunite in doubles on a wild card. MLB: Rays won 8th straight 12-4 over Athletics Aug 11, Taylor Walls homered from both sides, Nick Martinez complete game; Rays 73-46 lead AL East. WNBA: Fever 106-92 over Liberty Aug 11 (Kelsey Mitchell 28, Caitlin Clark double-double); Rivals Week Aug 8-14. NFL: preseason Wk1 Aug 13-15 all 32 teams; No.1 pick Fernando Mendoza debuts for Raiders vs ARI; Cowboys at SEA; Rams-Chiefs; Harbaugh's Giants host Vikings; Rodgers says no advantage to preseason snaps while McCarthy wants him to play. Golf: FedEx St. Jude Championship Aug 13-16 TPC Southwind, $20M purse, 750 pts, top 70 no cut, top 50 advance; Scheffler #1, Rose defending champ, Fleetwood defending FedExCup, McIlroy returns. Soccer: FC Cincinnati lost 2-1 to Atlas Aug 11 (Evander 44'), finish league phase 2-1, 6 pts; QFs Aug 25-27. NBA: Dillon Brooks 3yr/$73M ext with PHX Aug 8; Lonnie Walker IV to DEN, KCP to PHI. NHL: Calvin Pickard 1yr/$1M MIN; Hendrix Lapierre 2yr/$1.3M AAV PIT |
| Aug 12 | Deaths | Fiorenza Marchegiani (73, Italian actress, Aug 11); Andrzej Zaborski (75, Polish actor/theatre director, Aug 11); Vyacheslav Vorobyov (63, Russian footballer Kuban/KAMAZ, Aug 11); Alejandro Castellanos (46, Honduran swimmer, heart attack, Aug 10); Tommy Detamore (70, Texas steel guitarist/producer, Aug 5). Carried over as "still in the news": Don Nelson (86), Ben Jones (84), Jorge Messi (68) |
| Aug 12 | Current Events | Colombia M7.4 quake death toll passes 200 (forensic institute received 202 bodies); strongest in 47 years; foreign aid arriving; first crisis for new president Abelardo de la Espriella. Minnesota primaries Aug 11: Amy Klobuchar wins DFL gubernatorial nod (first woman to lead a major MN gov ticket), faces GOP House Speaker Lisa Demuth, who beat Trump-endorsed Mike Lindell (Demuth also first woman for her party); open Senate seat = Peggy Flanagan (D) vs Michele Tafoya (R), the former Sunday Night Football sideline reporter. Connecticut: Luke Bronin unseats 14-term Rep. John Larson in CT-01 Dem primary. Wisconsin: David Crowley wins Dem gubernatorial primary over Francesca Hong. Iran-Oman reported near a deal to reopen the Strait of Hormuz |


## August 13, 2026 (v46)

### Capitals
| Week | Question | Answer |
|------|----------|--------|
| Aug 13 | Bhutan | Thimphu (few/no traffic lights) |
| Aug 13 | Namibia | Windhoek |
| Aug 13 | Latvia | Riga |
| Aug 13 | Suriname | Paramaribo (only Dutch-speaking country in South America) |

### Classic TV
| Week | Show | Character | Actor |
|------|------|-----------|-------|
| Aug 13 | The Andy Griffith Show (1960-68) | Deputy Barney Fife | Don Knotts |
| Aug 13 | The Wild Wild West (1965-69) | James West | Robert Conrad |
| Aug 13 | All in the Family (1971-79) | Archie Bunker | Carroll O'Connor |
| Aug 13 | Banacek (1972-74) | Thomas Banacek | George Peppard |
| Aug 13 | Cheers (1982-93) | Sam Malone | Ted Danson |
| Aug 13 | Moonlighting (1985-89) | Maddie Hayes | Cybill Shepherd |

### Arts & Literature
| Week | Topic / Question | Answer |
|------|-----------------|--------|
| Aug 13 | Crime and Punishment (1866) author | Fyodor Dostoevsky |
| Aug 13 | Girl with a Pearl Earring (c.1665) painter | Johannes Vermeer |
| Aug 13 | The Four Seasons (c.1725) composer | Antonio Vivaldi |
| Aug 13 | "Do I dare to eat a peach?" / The Love Song of J. Alfred Prufrock poet | T.S. Eliot |
| Aug 13 | Slaughterhouse-Five (1969), "So it goes" author | Kurt Vonnegut |
| Aug 13 | Sculptor of David (1504) / Sistine Chapel ceiling | Michelangelo |

### Founded & Invented
| Week | Question | Answer |
|------|----------|--------|
| Aug 13 | Barbie creator / year | Ruth Handler, Mattel, 1959 - named for daughter Barbara (Ken = son) |
| Aug 13 | Monopoly - patent vs true origin | Charles Darrow patented 1935; descends from Lizzie Magie's 1904 "The Landlord's Game," designed to criticize land monopolies |
| Aug 13 | Corn flakes inventors | Kellogg brothers, Battle Creek MI - 1894 accident with left-out boiled wheat; company founded 1906 |
| Aug 13 | Dishwasher inventor | Josephine Cochrane, 1886 - wealthy hostess tired of servants chipping her china |
| Aug 13 | Duct tape origin | 1943 - Vesta Stoudt's idea, manufactured by Johnson & Johnson to waterproof WWII ammo boxes; originally "duck tape" |
| Aug 13 | Procter & Gamble founded | 1837, Cincinnati - William Procter (candlemaker) & James Gamble (soapmaker), brothers-in-law pushed together by their father-in-law |
| Aug 17 | Coca-Cola invented | John Pemberton, Atlanta pharmacist, 1886; bookkeeper Frank Robinson named it and wrote the script logo |
| Aug 17 | Post-it Notes origin | Spencer Silver's failed weak adhesive at 3M 1968; Art Fry used it for hymnal bookmarks; national launch 1980 |
| Aug 17 | Ford Motor Company founded | 1903, Detroit — Henry Ford's third car company; Model T 1908 |
| Aug 17 | Teflon inventor | Roy Plunkett, DuPont, 1938 — accident, gas cylinder polymerized to white powder |
| Aug 17 | Amazon's original name | "Cadabra" — 1994, Bezos, Bellevue WA garage; changed after a lawyer misheard it as "cadaver" |
| Aug 17 | Graeter's founded (Local) | 1870, Cincinnati — Louis Charles Greater, street cart; French pot process, 2 gallons at a time |

### General Trivia
| Week | Category | Topic/Fact |
|------|----------|-----------|
| Aug 13 | Trivia | Guinness Book of Records invented 1954 to settle pub arguments - Guinness MD lost a bet about Europe's fastest game bird |
| Aug 13 | Geography | Alaska is both westernmost AND easternmost US state - Aleutians cross the 180th meridian |
| Aug 13 | Language | "Avocado" from Nahuatl ahuacatl, which also meant "testicle" |
| Aug 13 | Sports | Stanley Cup misspellings are never corrected - 1972 Bruins engraved "BQSTQN BRUINS" |
| Aug 13 | Food | Ketchup sold as medicine in the 1830s - "tomato pills" for indigestion/diarrhea/jaundice |
| Aug 13 | Body | You're ~1 cm taller in the morning - spinal discs compress over the day |
| Aug 13 | Space | Astronauts say space smells like seared steak or spent gunpowder |
| Aug 13 | History | Wyoming gave women the vote in 1869 - 51 yrs before the 19th Amendment; refused statehood in 1890 without it |
| Aug 13 | Animals | A group of flamingos is a "flamboyance" |
| Aug 13 | Science | A teaspoon of healthy soil holds more microorganisms than there are people on Earth |
| Aug 13 | Pop Culture | "Happy Birthday to You" under copyright until a 2016 court settlement put it in public domain |
| Aug 13 | Local (Cincinnati) | Cincinnati chili "ways" (3/4/5-way) from Macedonian brothers Tom & John Kiradjieff, Empress Chili 1922, next to a burlesque house |

### Songs
| Week | Song | Artist | Year |
|------|------|--------|------|
| Aug 13 | Jeremy | Pearl Jam | 1991 |
| Aug 13 | Self Esteem | The Offspring | 1994 |
| Aug 13 | Ironic | Alanis Morissette | 1996 |
| Aug 13 | Hanging by a Moment | Lifehouse | 2001 |
| Aug 13 | In da Club | 50 Cent | 2003 |
| Aug 13 | Kids | MGMT | 2008 |

### This Day in History
| Week | Date Used | Events |
|------|-----------|--------|
| Aug 13 | August 13 (Berlin Wall - East Germany seals the border overnight across 27 miles 1961, 65th anniversary; Tenochtitlan falls to Cortes after 93-day siege 1521, 505 yrs, last emperor Cuauhtemoc; coin-operated pay telephone patented by William Gray of Hartford CT 1889; also Florence Nightingale dies 1910 and Opha May Johnson becomes first woman to enlist in US Marine Corps 1918) | - |
| Aug 17 | August 17 (Robert Fulton's North River Steam Boat leaves NYC for Albany 1807; Woodstock's scheduled final day 1969 — Hendrix closed Monday morning Aug 18; Double Eagle II first transatlantic balloon flight lands near Paris 1978; first commercial compact disc pressed 1982 — ABBA's The Visitors)  |
| Aug 13 | National Days: International Lefthanders Day; National Prosecco Day; National Filet Mignon Day; National Blame Someone Else Day; Central African Republic Independence Day (1960) | - |

### Sports / Current Events
| Week | Topic | Detail |
|------|-------|--------|
| Aug 13 | Reds | 57-62 (.479), 4th NL Central, 16.0 GB (Brewers 74-47); last 5 L-L-L-W-L (streak L1, 5-5 L10); shut out 5-0 by White Sox Aug 12 after a 5-4 extras win Aug 11; 6 of last 8 lost; Pirates 58-64 a half game back. TODAY @ Chicago White Sox 2:10 PM ET (getaway day, series finale). Source: MLB Stats API |
| Aug 13 | Box Office | Spider-Man: Brand New Day #1. NEW ANGLE USED: all-time chart position - ~$1.67B WW ($654.3M dom / $1.013B intl), 12th-highest-grossing film ever; $1B in 6 days (2nd fastest ever behind Endgame's 3 days) and 2nd fastest to $1B international; now chasing $2B, which only 7 films have ever reached; became highest-grossing film of 2026 in 7 days. Opening Aug 14-16: The End of Oak Street (David Robert Mitchell, WB, $30-45M), PAW Patrol: The Dino Movie (Cal Brunker, $14-19M), The Brink of War (Jeff Daniels as Reagan / J.K. Simmons as Gorbachev), Six: The Musical Live! |
| Aug 13 | Sports | NFL: preseason Wk1 opens TONIGHT - Lions at Bengals 7:00 PM ET Paycor Stadium (local angle); 6 Thursday games, all 32 teams Aug 13-15 (Packers-Steelers 7:00 NFL Net, Colts-Patriots 7:30, Cardinals-Raiders 8:00, Chargers-Texans 8:00, Titans-49ers 9:00 NFL Net). Tennis: Cincinnati Open main draw opens TODAY in Mason OH thru Aug 23; Jack Draper & Gael Monfils headline day 1; Wednesday qualifying washed out by rain. Golf: FedExCup Playoffs open - FedEx St. Jude Championship, TPC Southwind Memphis, 69 players no cut, top 50 advance; Scheffler & McIlroy paired 9:30 AM ET. MLB: Rays win 9th straight 8-4 at Athletics, 74-46 best record in baseball; Cubs 12-6 over Nationals to 71-50; Brewers lose 3rd straight 4-3 at San Diego, NL Central lead down to 3. WNBA: Aces 86-76 snapped Mystics' 7-game win streak (A'ja Wilson 26/13/4blk, 17th double-double; Jackie Young 25); Fever 106-94 Mercury; Liberty 92-76 Sparks. Soccer: Inter Miami eliminated from Leagues Cup, lost 3-2 at home to Club Leon Aug 12, Messi off the bench after returning from his father's funeral; PSG beat Aston Villa 2-1 in Salzburg to retain UEFA Super Cup (Kvaratskhelia 20') |
| Aug 13 | Deaths | Reggie Bannister (80, Reggie in the Phantasm series, Aug 9, Crestline CA, Lewy body dementia/Parkinson's); Robby Albarado (52, jockey, 5,000+ wins, Curlin's regular rider, Saratoga Springs NY after heart surgery); Jon Cypher (94, Chief Fletcher Daniels on Hill Street Blues / Gen. Marcus Craig on Major Dad, Aug 3, Central Point OR); David Z (78, Grammy-winning producer/engineer, Purple Rain, Prince/Fine Young Cannibals/Etta James, Aug 2 Burbank CA). Carried over: Fiorenza Marchegiani (73, Aug 11). NOTE: search engine falsely reported Brenda Fricker as dying Aug 13, 2026 - she actually died in July 2026; do not reuse |
| Aug 13 | Current Events | Karoline Leavitt stepping down as White House press secretary at end of August (Trump announced Aug 12 on Truth Social); at 28 the youngest ever in the role and first to give birth while serving (2nd child in May); staying on as outside adviser. Iran rejects Trump's claim the Strait of Hormuz is open/under US control - Persian Gulf Strait Authority says it remains blocked. Wisconsin governor's race set: David Crowley narrowly beat Francesca Hong for the Dem nod, faces Rep. Tom Tiffany in November. Putin issued an escalation warning aboard a missile warship during a naval exercise. China calls the India border "generally stable" amid Arunachal Pradesh tension; rejected India's renaming of 27 places |


---

## August 17, 2026 (v47)

### Capitals
| Week | Question | Answer |
|------|----------|--------|
| Aug 17 | Ethiopia | Addis Ababa (also HQ of the African Union) |
| Aug 17 | Vietnam | Hanoi (not Ho Chi Minh City) |
| Aug 17 | Iceland | Reykjavík (northernmost capital of a sovereign state) |
| Aug 17 | Fiji | Suva (on Viti Levu; people guess Nadi) |

### Classic TV
| Week | Show | Character | Actor |
|------|------|-----------|-------|
| Aug 17 | Columbo (1971–2003) | Lt. Columbo | Peter Falk |
| Aug 17 | The Mary Tyler Moore Show (1970–77) | Lou Grant | Ed Asner |
| Aug 17 | The Untouchables (1959–63) | Eliot Ness | Robert Stack |
| Aug 17 | Sanford and Son (1972–77) | Fred Sanford | Redd Foxx |
| Aug 17 | Miami Vice (1984–90) | Det. Sonny Crockett | Don Johnson |
| Aug 17 | The Six Million Dollar Man (1974–78) | Steve Austin | Lee Majors |

### Arts & Literature
| Week | Topic / Question | Answer |
|------|-----------------|--------|
| Aug 17 | The Old Man and the Sea (1952) author | Ernest Hemingway (Pulitzer 1953, Nobel 1954) |
| Aug 17 | "It was the best of times, it was the worst of times" opener | A Tale of Two Cities — Charles Dickens |
| Aug 17 | The Great Wave off Kanagawa (c.1831) printmaker | Katsushika Hokusai |
| Aug 17 | "New World" Symphony No. 9 (1893) composer | Antonín Dvořák (written in New York) |
| Aug 17 | "Do not go gentle into that good night" poet | Dylan Thomas (villanelle, for his dying father) |
| Aug 17 | Beloved (1987) author | Toni Morrison (Pulitzer 1988; Nobel 1993) |

### Founded & Invented
| Week | Question | Answer |
|------|----------|--------|
| Aug 17 | Coca-Cola invented | John Pemberton, Atlanta pharmacist, 1886; bookkeeper Frank Robinson named it and wrote the script logo |
| Aug 17 | Post-it Notes origin | Spencer Silver's too-weak adhesive at 3M 1968; Art Fry used it for hymnal bookmarks; national launch 1980 |
| Aug 17 | Ford Motor Company founded | 1903, Detroit — Henry Ford's third attempt at a car company; Model T 1908 |
| Aug 17 | Teflon inventor | Roy Plunkett, DuPont, 1938 — accident; a supposedly empty gas cylinder had polymerized to white powder |
| Aug 17 | Amazon's original name | "Cadabra" — 1994, Bezos, Bellevue WA garage; changed after a lawyer misheard it as "cadaver" |
| Aug 17 | Graeter's founded (Local) | 1870, Cincinnati — Louis Charles Greater, street cart; still French pot process, 2 gallons at a time |

### General Trivia
| Week | Category | Topic/Fact |
|------|----------|-----------|
| Aug 17 | History | Cleopatra lived closer in time to the Moon landing than to the building of the Great Pyramid |
| Aug 17 | Geography | Africa is the only continent in all four hemispheres |
| Aug 17 | Science | Mpemba effect — hot water can freeze faster than cold under some conditions; named for a Tanzanian schoolboy, 1963 |
| Aug 17 | Food | A pineapple plant takes about two years to produce a single fruit |
| Aug 17 | Animals | A group of owls is a "parliament" |
| Aug 17 | Space | Jupiter's Great Red Spot is shrinking — ~3 Earths wide a century ago, ~1 Earth now |
| Aug 17 | Language | "Nerd" first appeared in print in Dr. Seuss's If I Ran the Zoo (1950) |
| Aug 17 | Sports | Basketball's first hoops (1891) were peach baskets — someone climbed a ladder after every score |
| Aug 17 | Pop Culture | Sean Connery wore a toupee in every James Bond film he made |
| Aug 17 | Did You Know | Eiffel Tower had a 20-year permit and was slated for demolition; saved because it worked as a radio antenna |
| Aug 17 | Body | A 2014 study estimated the human nose distinguishes ~1 trillion smells; the "10,000" figure came from a 1927 guess |
| Aug 17 | Local (Cincinnati) | Music Hall was built over a Potter's Field / paupers' cemetery; remains uncovered again in the 2016–17 restoration |
| Aug 17 | Reds bar-bet | First MLB night game: May 24, 1935, Crosley Field, Reds 2–1 Phillies; FDR threw the switch from the White House |

### Songs
| Week | Song | Artist | Year |
|------|------|--------|------|
| Aug 17 | Black Hole Sun | Soundgarden | 1994 |
| Aug 17 | No Rain | Blind Melon | 1992 |
| Aug 17 | Gangsta's Paradise | Coolio feat. L.V. | 1995 |
| Aug 17 | Bitter Sweet Symphony | The Verve | 1997 |
| Aug 17 | Clocks | Coldplay | 2002 |
| Aug 17 | Seven Nation Army | The White Stripes | 2003 |

### This Day in History
| Week | Date Used | Events |
|------|-----------|--------|
| Aug 17 | August 17 (Robert Fulton's North River Steam Boat departs NYC for Albany 1807; Woodstock's scheduled final day 1969 — overran into Monday, Hendrix closed at ~9am Aug 18 to ~30,000 left; Double Eagle II completes first transatlantic balloon flight, lands near Paris 1978; first commercial compact disc pressed 1982 at a Philips plant in Germany — ABBA's The Visitors, 44th anniversary) | - |
| Aug 17 | National Days: National Thrift Shop Day; Black Cat Appreciation Day; National Nonprofit Day; National Massachusetts Day; Balloon Airmail Day; National I Love My Feet Day; Indonesia Independence Day (1945); Gabon Independence Day (1960); Discovery Day (Yukon) | - |

### Sports / Current Events
| Week | Topic | Detail |
|------|-------|--------|
| Aug 17 | Reds | 59-64 (.480), 5th/last NL Central, 17.0 GB (Brewers 77-48); last 5 oldest→newest L-W-W-L-L (streak L2, 4-6 L10); won 1-0 over Miami Aug 14, then lost 8-4 and 7-1 to drop the homestand series; now behind Pittsburgh (61-65) for last place. TODAY: split doubleheader vs St. Louis at GABP — G1 1:40 PM ET (makeup of 5/24 PPD), G2 6:40 PM ET (Rhett Lowder). Source: MLB Stats API |
| Aug 17 | Box Office | Spider-Man: Brand New Day #1 third straight weekend, $70.0M (-51%), $785.8M domestic in 17 days. NEW ANGLE USED: crossed $2B worldwide over the weekend — 8th film ever, new Sony record; and its $360M opening weekend broke Avengers: Endgame's all-time domestic opening record ($357M, held since 2019). Behind: The Odyssey $23.2M ($504.7M dom), The End of Oak Street $21.0M (new), PAW Patrol: The Dino Movie $20.5M (new). Weekend total $160.1M. Opening Aug 21-23: Mutiny (Jason Statham), Insidious: Out of the Further (Jacob Chase / Amelia Eve), The Magic Faraway Tree (Andrew Garfield, Claire Foy, Nicola Coughlan), Tony (Matt Johnson, Dominic Sessa as young Anthony Bourdain) |
| Aug 17 | Sports | Tennis (LOCAL): Cincinnati Open running Aug 13-23 at Lindner Family Tennis Center, Mason OH — Sabalenka needed 6 match points to beat Talia Gibson 6-2 7-6(2); Ben Shelton upset by 79th-ranked Jaime Faria of Portugal 6-4 6-4 (Faria's first top-10 win); Rybakina d. Townsend, Andreeva d. Oliynykova 6-1 6-0, Swiatek (def champ) d. Arango 6-3 6-0, Gauff d. Samsonova 2-6 6-4 6-1, Auger-Aliassime d. Tsitsipas 6-3 7-5, Medvedev d. Trungelliti, Fritz d. Michelsen (smashed racquet). NFL (LOCAL): Bengals beat Lions 16-14 in preseason opener Aug 13 at Paycor; PS Wk2 Aug 20-23, Bengals at Eagles. Golf: Scottie Scheffler won the FedEx St. Jude Championship at -17, TPC Southwind; BMW Championship Aug 18-23 at Bellerive, top 50. MLB: Brewers 77-48 best record, took 3 of 4 at Dodger Stadium; Orioles swept Rays at the Trop to take the last AL WC spot (Rays best home record in the sport 41-21). WNBA: Lynx 92-87 over Aces Aug 15 (Olivia Miles 23/8, Napheesa Collier 19); Valkyries 24-9. NASCAR: Joey Logano won at Richmond Aug 15 (2nd of 2026); Kyle Larson won 4th Knoxville Nationals hours later. Soccer: Arsenal 3-0 Man City in the Community Shield Aug 16; PL opens Aug 21 (Arsenal v Coventry City); Barcelona agreed deal with Man City for Rodri; Ronaldo says "probably my last year"; Cameroon beat Malawi for first WAFCON title. Leagues Cup QFs Aug 25-26: Austin-Toluca, Leon-RSL, America-Columbus Crew, Chicago Fire-Monterrey |
| Aug 17 | Deaths | Tommy John (83, LHP, 288 wins over 26 seasons, 4x All-Star, last pitch at 46; the 1974 Frank Jobe elbow reconstruction is named for him; died Sat Aug 15); Hayden Panettiere (36, Heroes / Nashville / Scream, found dead Aug 16 in Greenville SC, no signs of foul play, cause not released, memoir "This Is Me: A Reckoning" this year); Ruby Andrews (79, Chicago soul singer, "Casanova (Your Playing Days Are Over)", Aug 13); Prichard Colon (33, Puerto Rican boxer, brain injury from a 2015 bout, Aug 13); Christy Knowings (46, comedian, Nickelodeon's All That, Aug 11, severe asthma attack); Tyler Duckworth (44, MTV The Challenge: The Duel winner, announced Aug 13) |
| Aug 17 | Current Events | Colombia earthquake (M7.4, Aug 10, San Jose del Palmar, most powerful this century) death toll now at least 288 with 200+ missing; Cali, Pereira, Quibdo, Manizales damaged. Historic Indiana flooding — 11+ inches of rain east of Indianapolis pushed the White River past its 1913 record, cresting ~24.9 ft at Noblesville, a foot over a 113-year mark; at least 7 deaths; Gov. Mike Braun state of emergency, National Guard, federal aid request. US and Iran missed their 60-day nuclear deadline; USS Washington heading to the Middle East to relieve the USS Lincoln. Kansas City Royals will play the 2027 Field of Dreams game in Dyersville IA vs the Red Sox |

## August 19, 2026 (v48)

### Reds
| Aug 19 | Record | 60–66, 5th NL Central, 18.0 GB (Brewers 78–48), .476, 7.5 back of last NL WC; L1 streak; 4–6 last 10; last 5 L,L,L,W,L. Split DH with STL Aug 17 (L 1–2, W 6–5), shut out 3–0 Aug 18. Today: Cardinals at Reds 6:40 PM ET. Source: MLB Stats API |

### Box Office
| Aug 19 | #1 | Spider-Man: Brand New Day — $70,711,990 weekend (-51%), $786.5M domestic in 17 days, past $2.02B worldwide (highest-grossing Spider-Man ever). Fun facts used: $47M opening Monday = biggest single Monday in history (beat Black Panther 2018); $1B in six days, 2nd-fastest ever; dir. Destin Daniel Cretton. Behind: The Odyssey $23.6M, The End of Oak Street $21.0M (new), PAW Patrol: The Dino Movie $20.3M (new). Weekend total $163.1M / 61 titles |
| Aug 19 | Coming Aug 21–23 | Mutiny (Jason Statham); Insidious: Out of the Further (Lin Shaye, Brandon Perea); Spa Weekend (Palm Springs comedy); The Magic Faraway Tree (Garfield/Foy/Coughlan) |

### Sports / Deaths / Current Events
| Aug 19 | Sports | Tennis (LOCAL): Cincinnati Open Aug 13–23, Lindner Family Tennis Center, Mason — Mon R32: Zverev d. Atmane 7-6(4) 7-6(6); Rafael Jodar d. Tabilo 6-2 6-1 (3 games lost); Fils upset Lehecka; de Minaur, Cobolli, Mensik, Tommy Paul through; Fonseca withdrew injured; semis Aug 22, final Aug 23. NFL (LOCAL): Bengals host Chicago Bears preseason Wk2 Sat Aug 22, 7:00 PM ET at Paycor. MLB: Brewers 78-48 best record; Rays 75-49 lead AL; Dodgers 11-5 over Rockies Mon w/ 2 Ohtani HRs; AL Central four teams within 5.5. Golf: BMW Championship Aug 20-23 at Bellerive CC, St. Louis (top 50 → top 30). WNBA: Fever offense surging into playoffs (Clark/Mitchell); first-ever Fever trip to Toronto Tempo Aug 18. NASCAR: Joey Logano won Cook Out 400 at Richmond Aug 15 (2nd of 2026). Soccer: Premier League 2026-27 opens Fri Aug 21; Arsenal 3-0 Man City Community Shield Aug 16 |
| Aug 19 | Deaths | O.J. Brigance (56, Ravens/Dolphins LB, first tackle of Super Bowl XXXV, only man to win both a Grey Cup and Super Bowl, ALS complications Aug 17); Laura Cardoso (98, Brazilian actress, ~7 decades, Aug 18); Fulvio Lucisano (98, Italian film producer, Aug 18); Mike Bailey (84, English footballer/manager — Charlton, Wolves, England — dementia complications Aug 17); Vedrana Rudan (76, Croatian journalist/novelist, Aug 18); Abdelaziz Guerda (79, Algerian actor/stage director, Aug 17) |
| Aug 19 | Current Events | Meta child-safety trial opened Aug 18 in Oakland (state AGs allege Facebook/Instagram designed to addict minors). Florida primaries Aug 18 — Angie Nixon, democratic socialist, won the Democratic US Senate primary. US–Iran 60-day MOU expired with no deal; White House won't extend. Oman oil spill now spread across 2,000+ sq km and fouling beaches. Tropical Storm Lala damaged homes on Hawaii's Big Island; flooding across Midwest/Appalachia, heat alerts in the South. Border-wall construction in Big Bend National Park paused pending on-the-ground review |


---

## August 20, 2026 (v49)

### Reds
| Aug 20 | Record | 61–66, 5th NL Central, 17.0 GB (Brewers 78–49), .480, 6.5 back of last NL WC; W1 streak; 5–5 last 10; last 5 (old→new) L,L,W,L,W. Beat STL 5–4 Aug 19 after being shut out 3–0 Aug 18. Today: Cardinals at Reds 12:40 PM ET day game, series finale, then @ ARI. Source: MLB Stats API |

### Box Office
| Aug 20 | #1 | Spider-Man: Brand New Day — $70,711,990 weekend (Aug 14 wknd still current), $786.5M domestic in 17 days, past $2.02B WW. Fun fact used THIS run: Glasgow doubled for NYC; three full city blocks built at Pinewood. (Aug 19 used the Monday record / $1B in six days / Cretton facts — do not reuse.) Behind: The Odyssey $23.6M, End of Oak Street $21.0M, PAW Patrol: Dino Movie $20.3M, Katseye: Wild Hearts $4.0M. Weekend total $163.1M / 63 titles |
| Aug 20 | Coming Aug 21–23 | Mutiny (Statham, cargo ship revenge); Insidious: Out of the Further (Amelia Eve travels into The Further); Spa Weekend (Palm Springs comedy); The Magic Faraway Tree (Garfield/Foy/Coughlan) |

### Sports / Deaths / Current Events
| Aug 20 | Sports | Tennis (LOCAL): Cincinnati Open — top seeds OUT. Sara Bejlek (No. 35) d. world No. 1 Sabalenka 7-6(9-7) 6-4 (first top-10 win); Tommy Paul saved MP and d. top seed Zverev 4-6 7-6(8-6) 6-4; Gauff through 6-3 6-2 over Bouzkova; Alcaraz withdrew (wrist). QFs Aug 20–21, final Aug 23. MLB: Brewers 22–0 over Mariners Aug 18 — tied franchise record for runs, tied modern MLB record for largest shutout margin (Yelich, Hamilton, Bauers, Lara HRs). Golf: BMW Championship Aug 20–23 Bellerive CC St. Louis, $20M purse, no cut, 50 players, top 30 advance; Scheffler leads FedExCup, McIlroy in field; par 70 / 7,448 yds. NFL (LOCAL): Bengals 16–14 over Lions in preseason opener; host Bears Sat Aug 22 7 PM ET; traded No. 10 pick to NYG for DT Dexter Lawrence, signed edge Boye Mafe. WNBA: Lynx first to clinch; FIBA World Cup break early Sept, resume Sept 17, playoffs tip Sept 27. Soccer: Premier League 2026-27 opens Fri Aug 21; Arsenal 3-0 Man City in Community Shield Aug 16 |
| Aug 20 | Deaths | Frank Beard (77, ZZ Top drummer — the one WITHOUT a beard, Aug 18); Hayden Panettiere (36, Claire Bennet on Heroes / Juliette Barnes on Nashville, Aug 16); Tommy John (83, 288-win pitcher, namesake of the elbow surgery Dr. Frank Jobe pioneered on him in 1974, Aug 15); Nikki Ross (52, singer, Aug 14); Prichard Colón (33, Puerto Rican boxer, 2015 brain injury, Aug 13); Christy Knowings (46, Nickelodeon All That, asthma attack, Aug 11); Ben "Cooter" Jones (84, Dukes of Hazzard + two terms in Congress from Georgia, Aug 9); O.J. Brigance (56, only man to win a Grey Cup and a Super Bowl, ALS, Aug 17) |
| Aug 20 | Current Events | Trump: "no talks or conversations" with Tehran, US naval blockade of Iranian ports remains in full force (mines cleared, other shipping passing); threatened to bomb Oman over its Iran/Hormuz shipping deal. Hormuz traffic slowed again Tuesday. 50% tariff increase on Canadian goods paused three days after Carney call. Israeli strikes killed at least seven Palestinians in Gaza. Sanctions imposed on ICC President and Senior Prosecutor. San Diego Padres staffer in ICE custody after Texas airport arrest. Meta child-safety trial (opened Aug 18, Oakland) ongoing |



## August 24, 2026 (v50)

### Reds
| 62–69, 5th NL Central, 19.0 GB (Brewers 81–50), .473, L1 streak, 3–7 L10. Last 5: W(5-4 STL), L(9-10 STL), L(0-9 @ARI), W(11-5 @ARI), L(3-5 @ARI). Today: @ San Francisco Giants 9:45 PM ET. Bar-bet: Frank Robinson only MVP in both leagues. Source: MLB Stats API. |

### Box Office
| #1 Spider-Man: Brand New Day, ~$39M 4th weekend, ~$855M domestic. Fun fact used: 7th-biggest 4th weekend ever; first film to lead four straight weekends since Avatar: Fire and Ash. Insidious: Out of the Further opened ~$25M. Coming Aug 28–30: Coyote vs. ACME, The Dog Stars, Buddy, Colony. |

### Sports / Deaths / Current Events
| Sports: Wyndham Clark won BMW Championship at Bellerive (3rd 2026 win); US Open qualifying/Fan Week begins Aug 24, main draw Aug 30; NFL preseason wk 2 — Bengals 27-9 over Bears (Aug 22), Nick Chubb retired, Kamara out a month, Higgins ACL, Biadasz indefinite; Brewers 81-50 best NL record; WNBA regular season ends Sept 24. |
| Deaths: Nancy Kassebaum Baker (94, Aug 21, first woman elected to US Senate without following a husband); Bunny Levine (97, Aug 22, Gilmore Girls / Adam Sandler films); Michael Wright (70, Aug 19, The Five Heartbeats, Oz). NOTE: search engines surfaced Bob Weir as a current-week death — he actually died January 2026; do not reuse. |
| Current events: Pentagon Iran war casualty count to 775 (18 deaths); Tropical Storm Moke hits Big Island a week after Hurricane Lala; Meta/Google/OpenAI/Amazon pledge own power+water costs after Abbott's Texas freeze; Trump renews Canada tariff criticism; Venezuela flooding. |
| NOTE: This run executed on Monday Aug 24, 2026 (scheduled task fired off-Thursday). |

---

## August 25, 2026 (v51)

| Item | Detail |
|------|--------|
| Reds | 62–70 .470, 5th NL Central, 19.5 GB (Brewers 81–50); L2 streak; 3–7 last 10; last 5 L-L-W-L-L; @ SF Giants 9:45 PM ET. Verified via MLB Stats API. |
| Reds news | JJ Bleday hit for the cycle Aug 22 @ ARI (11–5 win) — 8th cycle in Reds history, first since Elly De La Cruz Jun 2023, 4th MLB cycle of 2026. |
| Box Office | Spider-Man: Brand New Day #1 4th weekend ~$39M (7th-best 4th weekend ever); $2B WW in 3 weeks (2nd-fastest); highest-grossing 2026 release in 7 days; opening wknd ~$355M global (2nd-biggest ever). Insidious: Out of the Further opened ~$25M. |
| Coming weekend | Aug 28–30: Coyote vs. ACME; The Dog Stars (Ridley Scott); Buddy; Colony. |
| MLB | Royals 8-game win streak; White Sox 68–62 lead AL Central by 3.5; Astros part with GM; Ohtani nearing mound return; Arenado passed 2,000 hits. |
| NFL | Cutdown to 53 by Sun Aug 30 6 PM ET; ~1,184 players released; waivers Mon Aug 31 1 PM ET. Bills signed S Geno Stone and OLB Mike Danna. |
| NBA | Giannis traded MIL→MIA (4 players + 4 firsts); Kawhi to Toronto; LaMelo to Minnesota; Klay Thompson to Miami 2yr/$11.48M (Aug 23); Draymond back to GSW 1yr/$27.7M; DeRozan to Denver. |
| NHL | Montreal signs Ivan Demidov 8yr × $9.15M AAV; max contract term drops 8→7 years next month; only 5 max-term deals since FA opened. |
| MLS | Messi scored vs Philadelphia Aug 19; 923 career goals; 14G/10A in 18 MLS games; Inter Miami 2nd in East, 39 pts. |
| NCAA | FCS opens Thu Aug 27; Week 0 Sat Aug 29 (UNC vs TCU in Dublin noon ET; USC vs San Jose State 3 PM ET NBC); first full Saturday Sept 5. |
| Tennis | US Open qualifying began Mon Aug 24; main draw starts Aug 30. |
| Golf | Tour Championship / FedExCup finale in Atlanta this week; Tommy Fleetwood defending. |
| Deaths | Frank Beard (77, Aug 17, ZZ Top drummer, 57 years, the beardless one); Tommy John (83, Aug 16, 288 wins over 26 seasons, surgery namesake); Hayden Panettiere (36, Aug 16, Heroes/Nashville/Remember the Titans); Fulvio Lucisano (98, Aug 18, Italian producer); Laura Cardoso (98, Aug 18, Brazilian actress). |
| Current events | US "economic D-Day" Iran sanctions expected by week's end (Bessent); Iran threatens to halt Persian Gulf oil exports and calls support for sanctions an act of war; 1,000+ Navy dependents still displaced from Bahrain; Trump promises more Canada tariffs after talks collapse; 160+ deported to Haiti post-TPS; Israeli strike near Al-Aqsa Hospital kills two brothers. |
| NOTE | This run executed on Tuesday Aug 25, 2026 (scheduled task fired off-Thursday again). Box-office weekend is the same Aug 21–23 frame used in the v50 Aug 24 sheet — fresh angles were substituted ($2B/3wks, $355M opening, 2026 top-grosser in 7 days) rather than reusing the v50 fun fact. |


## August 26, 2026 (v52)

| Item | Detail |
|------|--------|
| Reds | 62–71 .466, 5th NL Central, 19.5 GB (Brewers 81–51); L3 streak; 3–7 last 10; last 5 (oldest→newest) L-W-L-L-L; @ SF Giants 3:45 PM ET. Verified via MLB Stats API. |
| Reds angle | 22–14 in one-run games, 9–4 in extras — they lose the blowouts, not the close ones. |
| Box Office | Spider-Man: Brand New Day #1 4th weekend $39.0M (Aug 21–23); $854.9M domestic in 24 days; $2.2B+ WW. Fresh angle used: $2B in 17 days (2nd-fastest behind Endgame's 11) + outgrossed every other 2026 release's full run in 7 days. #2 Insidious: Out of the Further $25.1M debut; #3 The Odyssey $19.7M ($539M). |
| Coming weekend | Aug 28–30: The Dog Stars (Ridley Scott); Coyote vs. ACME; Buddy; Cliffhanger (reboot). |
| MLB | Brewers 81–51 best record in baseball, +5.5 on Cubs in NL Central. JJ Bleday cycle Aug 22 (8th in Reds history). |
| NFL | Cutdown to 53 Sun Aug 30 6 PM ET; waivers Mon Aug 31 1 PM ET. Bengals: traded No. 10 pick for NT Dexter Lawrence, signed Jonathan Allen + Boye Mafe, re-signed Joe Flacco. |
| NBA | Allen Robinson retired on his 33rd birthday (Aug 25); Klay Thompson to Miami after clearing waivers; DeRozan 1-yr in Denver; Shaedon Sharpe out ~6 months (meniscus). |
| Tennis | US Open mixed doubles began Aug 25 — all doubles-specialist teams lost Day 1; Svitolina/Monfils beat No. 1s Siniáková/Patten. Singles main draw Aug 30. |
| Golf | Tour Championship / FedExCup finale tees off Thu Aug 27 at East Lake. Scheffler No. 1 in standings; Fleetwood defending. |
| NCAA | Ohio State preseason AP No. 1 (9th time), then Oregon, Georgia, Notre Dame, Texas. FCS opens Thu Aug 27; Week 0 Sat Aug 29 — UNC vs TCU in Dublin; No. 14 USC hosts San Jose State. |
| MLS | Messi at 923 career goals; Inter Miami 2nd in East. |
| Deaths | **Dolly Parton, 80 (Aug 25)** — Queen of Country, died in Nashville after a brief battle with cancer; private family funeral. James Lew (73, Aug 23, stunt coordinator, Emmy for Luke Cage). Michael Wright (69, Aug 19, The Five Heartbeats). Nikki Ross (52, Aug 14, Houston gospel singer). |
| Current events | Dolly Parton tributes dominate the cycle; Iran defiant on new US sanctions while pursuing diplomacy via Oman/Pakistan; Canada retaliating in trade dispute after talks collapsed; Trump opened border to Mexican beef amid supply pinch; primaries in three states — Lindsey Graham's sister won the SC nomination to succeed him. |
| NOTE | Executed Wednesday Aug 26, 2026 (task again fired off-Thursday). Box-office weekend frame is still Aug 21–23 (third consecutive sheet on that frame) — used entirely new angles ($854.9M domestic/24 days, $2B in 17 days vs Endgame's 11) rather than repeating v50/v51 facts. |


## August 27, 2026 (v53)

| Section | Content |
|---------|---------|
| Reds | 63–71 .470, 5th NL Central, 19.5 GB (Brewers 82–51); W1; last 10 4–6; last 5 W-L-L-L-W (Aug 22 W11-5 @ARI, Aug 23 L3-5, Aug 24 L0-5 @SF, Aug 25 L1-3, Aug 26 W10-9); NO GAME TODAY, next Fri Aug 28 @ Cubs 2:20 ET. Source: MLB Stats API. |
| Box Office | Spider-Man: Brand New Day #1 4th straight weekend $39.0M (Aug 21–23); $854.9M dom / $2.22B WW. NEW ANGLE: 4 consecutive #1 weekends = 2026 record, breaking the 3-weekend tie with The Super Mario Galaxy Movie; 4th film ever past $800M domestic; 3rd-highest domestic release ever. #2 Insidious: Out of the Further $25.1M debut; #3 The Odyssey $19.7M. |
| Coming This Weekend | Aug 28–30: Coyote vs. ACME (Dave Green; Forte/Cena); The Dog Stars (Ridley Scott; Elordi/Qualley/Brolin); Buddy (Casper Kelly; Key/Oswalt); Finding Emily (Angourie Rice/Minnie Driver). |
| Sports | NFL cutdown Sun Aug 30 6 PM ET, 90→53, ~1,184 players cut; Bengals released OT Cody Ford, Ja'Marr Chase left Tue practice w/ left knee "tweak," missed Wed, not serious. MLB: Brewers 82–51 best record, White Sox 70–63 lead AL Central, Rays 79–54 AL East, postseason Sept 29. NCAA: FCS opens tonight, FBS opens Sat Aug 29 UNC vs TCU in Dublin. Golf: TOUR Championship East Lake Aug 27–30. Tennis: Muchová/Menšík won US Open mixed doubles over Bencic/Cobolli 6-3,1-6,[10-6]; singles main draw Aug 30. NBA: Klay Thompson to Miami Heat. NHL: 2026-27 ESPN schedule released. |
| Deaths | Dolly Parton (80, country icon, d. Aug 25 Nashville, cancer; flags half-staff nationwide 1 week); Hayden Panettiere (36, Heroes/Nashville, d. Aug 21); Latimore (86, "Let's Straighten It Out," d. Aug 22); James Lew (73, stunt coordinator, Emmy for Luke Cage, d. Aug 23); Janie Bradford (87, Motown songwriter "Money," d. Aug 21); Grace Nortey (89, Ghanaian actress, d. Aug 26). |
| Current events | Dolly Parton death dominates cycle; Meta multibillion-dollar settlement over child-harm claims; Boston federal judge vacated nationwide order blocking USPS work on mail-in voting limits; Iran resumed Oman talks on Strait of Hormuz; mass kidnapping in Haiti; Target pulled a kids' Halloween costume after minstrel-caricature backlash; data centers becoming a midterm issue. |
| NOTE | First actual-Thursday run in a while (v50–v52 fired Mon–Wed). Fourth consecutive sheet on the Aug 21–23 box-office frame — used the "4 straight #1 weekends = 2026 record / 3rd-highest domestic ever" angle, fresh vs v50–v52. |


## August 28, 2026 (v54)

| Section | Content |
|---------|---------|
| Reds | 63–71 .470, 5th NL Central, 20.0 GB (Brewers 83–51); W1; last 10 4–6; last 5 W-L-L-L-W (Aug 22 W11-5 @ARI, Aug 23 L3-5 @ARI, Aug 24 L0-5 @SF, Aug 25 L1-3 @SF, Aug 26 W10-9 @SF). TODAY: Fri Aug 28 @ Cubs 2:20 PM ET at Wrigley. Source: MLB Stats API. |
| Box Office | Spider-Man: Brand New Day #1 4th weekend $39.0M (Aug 21–23); $863.3M dom / $2.23B WW through Aug 26. NEW ANGLE (fresh vs v50–v53): the record $360M opening weekend — biggest debut in box office history, unseating Avengers: Endgame ($357.1M, 2019); Sunday estimate was $355M, actuals pushed it over Monday. #2 Insidious: Out of the Further $25.1M; #3 The Odyssey $19.7M. |
| Coming This Weekend | Aug 28–30: The Dog Stars (Ridley Scott; Elordi/Qualley/Pearce/Wong, IMAX); Coyote vs. ACME (Forte/Cena); Buddy (mascot horror-comedy); The Whisper Man (Netflix; Adam Scott/De Niro/Keaton/Monaghan). |
| Sports | NFL cutdown Sun Aug 30 6 PM ET, 90→53, ~1,184 cut; Bengals waived OT Cody Ford, swing tackle "still pretty open" per Zac Taylor, DL crunch w/ McKinnley Jackson & Kris Jenkins on bubble. NCAA: FCS Week 0 Thu; FBS opens Sat Aug 29, 8 games. Golf: TOUR Championship East Lake Aug 27–30, top 30 FedExCup. Tennis: US Open Aug 23–Sept 13, 22 days = longest edition ever, record $108M compensation (+20% vs $90M in 2025), Sabalenka top seed 8th straight slam. MLB: Brewers 83–51 best record; postseason Sept 29. NHL: TNT (72 games + 2027 Cup Final) & ESPN (100 exclusives) 2026-27 schedules out; season opens Sept 29 CAR-FLA and TOR-MTL; Quinn Hughes / Erik Karlsson trade chatter. |
| Deaths | Tim Curry (80, d. Aug 25, Rocky Horror/Clue/IT/Muppet Treasure Island, Toluca Lake, wheelchair since 2012 stroke); Peter Cullen (85, d. Aug 26, voice of Optimus Prime 40+ yrs and Eeyore); Shelley Fabares (82, d. Aug 22, Donna Reed Show/Coach, "Johnny Angel" #1 1962, m. Mike Farrell); Dolly Parton (80, d. Aug 25, carried over). |
| Current events | Himalayan flood on Nepal–Tibet border, Lhende Khola valley, 350+ dead / 1,300+ missing; Meta $17B settlement over teen social-media addiction; Iran blocked IAEA inspectors from bombed nuclear sites; Pentagon killed 4 in latest alleged drug-boat strikes; ICE arrests at Danbury CT school bus stops; Ukraine–Russia strikes, Moscow warns UK on arms; Dolly Parton death still dominating. |
| NOTE | Ran Friday Aug 28 (scheduled task fired a day past Thursday). Fifth consecutive sheet on the Aug 21–23 box-office frame — pivoted to the all-time opening-weekend record angle since the "4 straight #1 weekends" angle was spent in v53. Tim Curry / Peter Cullen deaths were both missed by v53 and are the headline obits this run. |


## August 31, 2026 (v55)

| Section | Content |
|---------|---------|
| Reds | 65–72 .474, 5th NL Central, 20.0 GB (Brewers 85–52); W1; last 10 4–6; last 5 L-W-W-L-W (Aug 25 L1-3 @SF, Aug 26 W10-9 @SF, Aug 28 W10-8 @CHC, Aug 29 L5-17 @CHC, Aug 30 W7-5 @CHC). TODAY: Mon Aug 31 vs San Diego Padres 6:40 PM ET at GABP. Source: MLB Stats API. |
| Box Office | NEW FRAME (Aug 28–30): Spider-Man: Brand New Day #1 for a 5th straight weekend, $22.2M (-43%), $891.5M domestic in 31 days. Whole 28-title chart only $69.2M. ANGLE (fresh vs v50–v54): it has passed Avengers: Endgame ($858.4M) for #2 all-time domestic, chasing Star Wars: The Force Awakens ($936.7M). #2 The Odyssey $14.3M ($563.8M total); #3 Insidious: Out of the Further $10.1M; #4 The Dog Stars $8.0M debut. Oddity: 2001's The Fast and the Furious charted on a re-release, day 9,201. |
| Coming This Weekend | Sept 4–6: Onslaught (Adam Wingard; Adria Arjona, Rebecca Hall, Drew Starkey, Michael Biehn, R); By Any Means (Yahya Abdul-Mateen II, Mark Wahlberg as Greg Scarpa, 1960s Mississippi, R); Cars: 20th Anniversary re-release (G); Tom and Jerry: Forbidden Compass (animated, 90 min). |
| Sports | Tennis: DJOKOVIC UPSET IN US OPEN R1 by Mariano Navone 7-6(5), 5-7, 4-6, 6-2, 6-1 — first-ever opening-round slam loss, ends record 78 straight R1 wins, earliest major exit since 2006 Aus Open, visibly ill, 70 UEs. Golf: Scottie Scheffler won TOUR Championship at East Lake by 3 over Viktor Hovland — 2nd FedExCup. MLB: White Sox 72–64 leading AL Central after three straight 100-loss seasons (verified via MLB Stats API). NFL: cutdown Sun Aug 30 6 PM ET; waivers awarded 1 PM ET Aug 31. Bengals finished preseason 3–0 — first undefeated preseason since 2006 and first of the Zac Taylor era, capped 30–13 at Philadelphia. NCAA: Week 0 Aug 29, No. 14 USC beat San Jose State 42–26 (only ranked team playing). MLS: Nashville SC 4, FC Cincinnati 0 (Aug 29 — Surridge, Mukhtar, Acosta, Qasem). NBA: Jonathan Kuminga 2yr/$12.4M to Minnesota; Bennedict Mathurin 2yr/$16M to New Orleans. |
| Deaths | King Harald V of Norway (89, d. Aug 28, Europe's oldest reigning monarch, king since 1991, fled Nazis as a child, Olympic sailor; succeeded by Haakon VIII); Ratko Mladić (84, d. Aug 27, convicted of genocide at The Hague); Mary Tsingou (97, d. Aug 27, Fermi–Pasta–Ulam–Tsingou problem, one of the first programmers); Larry Christenson (72, d. Aug 28, lifelong Phillie, 1980 WS); Rubén Rada (83, d. Aug 26, Uruguayan candombe); Jackie Glass (70, d. Aug 28, O.J. Simpson 2008 trial judge / Swift Justice); Tony Mundine (75, d. Aug 30, Australian boxer); Franco Fontana (92, d. Aug 29, Italian color photographer). Carried over: Dolly Parton, Tim Curry, Peter Cullen. |
| Current events | US struck two Iranian launchers on Larak Island Sun Aug 30 after IRGC prepared to fire rockets carrying sea mines into the Strait of Hormuz — first US strike on Iran since late July; IRGC fired ballistic missiles at King Hussein and al-Azraq bases in Jordan, Jordan intercepted 8 at dawn; month seven of the conflict. Norway: Haakon VIII succeeds Harald V. Ferry capsized off Northern Cyprus, 8 dead / 18 missing. Household squeeze coverage — airfares, buy-now-pay-later delinquencies. Dolly Parton death still dominant. |
| NOTE | Ran Monday Aug 31 (scheduled task continues to fire on non-Thursdays). First run on the Aug 28–30 box-office frame after five straight sheets on Aug 21–23. King Harald V died the morning of Aug 28 and was missed by v54 — headline obit this run. Djokovic's first-round US Open loss is the biggest single sports item of the week. Aug 31 calendar date had never been used for This Day in History. |


_Last updated: August 31, 2026 (v55)_
