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
| Apr 16 | Capital of Vermont | Montpelier |
| Apr 16 | Capital of Kazakhstan | Astana |
| Apr 16 | Capital of South Dakota | Pierre |
| Apr 16 | Capital of Morocco | Rabat |
| Apr 19 | Capital of Australia | Canberra |
| Apr 19 | Capital of Montana | Helena |
| Apr 19 | Capital of Kazakhstan | Astana |
| Apr 19 | Capital of Rhode Island | Providence |
| Apr 19 | Capital of Myanmar | Naypyidaw |
| Apr 19 | Capital of Vermont | Montpelier |
| Apr 20 | Capital of Montana | Helena |
| Apr 20 | Capital of Kazakhstan | Astana |
| Apr 20 | Capital of Wisconsin | Madison |
| Apr 20 | Capital of Myanmar | Naypyidaw |
| Apr 21 | Capital of Montana | Helena |
| Apr 21 | Capital of Kazakhstan | Astana |
| Apr 21 | Capital of Myanmar | Naypyidaw |
| Apr 21 | Capital of New Hampshire | Concord |
| Apr 23 | Capital of Montana | Helena |
| Apr 23 | Capital of Sri Lanka | Sri Jayawardenepura Kotte |
| Apr 23 | Capital of Nebraska | Lincoln |
| Apr 23 | Capital of Kazakhstan | Astana |
| Apr 23 | Capital of Vermont | Montpelier |
| Apr 23b | Capital of Bhutan | Thimphu |
| Apr 23b | Capital of Idaho | Boise |
| Apr 23b | Capital of Suriname | Paramaribo |
| Apr 23b | Capital of Louisiana | Baton Rouge |
| Apr 25 | Capital of Maine | Augusta |
| Apr 25 | Capital of Switzerland | Bern |
| Apr 25 | Capital of Oklahoma | Oklahoma City |
| Apr 25 | Capital of Mongolia | Ulaanbaatar |
| Apr 26 | Capital of Croatia | Zagreb |
| Apr 26 | Capital of Wyoming | Cheyenne |
| Apr 26 | Capital of Senegal | Dakar |
| Apr 26 | Capital of Delaware | Dover |
| Apr 26 | Capital of Uruguay | Montevideo |
| Apr 28 | Capital of Iowa | Des Moines |
| Apr 28 | Capital of Slovenia | Ljubljana |
| Apr 28 | Capital of Arkansas | Little Rock |
| Apr 28 | Capital of Ethiopia | Addis Ababa |
| Apr 29 | Capital of New Mexico | Santa Fe |
| Apr 29 | Capital of Latvia | Riga |
| Apr 29 | Capital of Kentucky | Frankfort |
| Apr 29 | Capital of Vietnam | Hanoi |
| Apr 30 | Capital of North Dakota | Bismarck |
| Apr 30 | Capital of Madagascar | Antananarivo |
| Apr 30 | Capital of Connecticut | Hartford |
| Apr 30 | Capital of Albania | Tirana |
| Apr 30b | Capital of Oregon | Salem |
| Apr 30b | Capital of Norway | Oslo |
| Apr 30b | Capital of New Zealand | Wellington |
| Apr 30b | Capital of Nigeria | Abuja |
| May 1 | Capital of Mississippi | Jackson |
| May 1 | Capital of Peru | Lima |
| May 1 | Capital of Finland | Helsinki |
| May 1 | Capital of Cambodia | Phnom Penh |
| May 1 | Capital of Georgia (US) | Atlanta |

| May 1v2 | Capital of West Virginia | Charleston |
| May 1v2 | Capital of Nepal | Kathmandu |
| May 1v2 | Capital of Trinidad and Tobago | Port of Spain |
| May 1v2 | Capital of Libya | Tripoli |

| May 2 | Capital of Tennessee | Nashville |
| May 2 | Capital of Argentina | Buenos Aires |
| May 2 | Capital of Maryland | Annapolis |
| May 2 | Capital of Iceland | Reykjavík |
| May 3 | Capital of Texas | Austin |
| May 3 | Capital of Michigan | Lansing |
| May 3 | Capital of Brazil | Brasília |
| May 3 | Capital of South Africa | Pretoria (executive) |
| May 4 | Capital of Hawaii | Honolulu |
| May 5 | Capital of Kansas | Topeka |
| May 5 | Capital of Qatar | Doha |
| May 5 | Capital of Florida | Tallahassee |
| May 5 | Capital of Namibia | Windhoek |
| May 5v2 | Capital of Colorado | Denver |
| May 5v2 | Capital of South Korea | Seoul |
| May 5v2 | Capital of Uganda | Kampala |
| May 5v2 | Capital of Czech Republic | Prague |
| May 4 | Capital of Egypt | Cairo |
| May 4 | Capital of Indiana | Indianapolis |
| May 4 | Capital of Portugal | Lisbon |


---

## 📺 Classic TV Used

| Week | Show | Character | Actor |
|------|------|-----------|-------|
| Apr 16 | M*A*S*H | Col. Sherman T. Potter | Harry Morgan |
| Apr 16 | Dallas | J.R. Ewing | Larry Hagman |
| Apr 16 | Cheers | Sam Malone | Ted Danson |
| Apr 16 | The X-Files | Dana Scully | Gillian Anderson |
| Apr 19 | M*A*S*H | Hawkeye Pierce | Alan Alda |
| Apr 19 | Cheers | Sam Malone | Ted Danson |
| Apr 19 | Murder, She Wrote | Jessica Fletcher | Angela Lansbury |
| Apr 20 | All in the Family | Archie Bunker | Carroll O'Connor |
| Apr 20 | The Rockford Files | Jim Rockford | James Garner |
| Apr 20 | Murder, She Wrote | Jessica Fletcher | Angela Lansbury |
| Apr 20 | Cheers | Sam Malone | Ted Danson |
| Apr 20 | The X-Files | Fox Mulder | David Duchovny |
| Apr 21 | Magnum, P.I. | Thomas Magnum | Tom Selleck |
| Apr 21 | WKRP in Cincinnati | (partial) | (unknown) |
| Apr 23 | M*A*S*H | Hawkeye Pierce | Alan Alda |
| Apr 23 | Magnum, P.I. | Thomas Magnum | Tom Selleck |
| Apr 23 | Married... with Children | Al Bundy | Ed O'Neill |
| Apr 23 | Star Trek: The Next Generation | Data | Brent Spiner |
| Apr 23 | Northern Exposure | Dr. Joel Fleischman | Rob Morrow |
| Apr 23 | Remington Steele | Remington Steele | Pierce Brosnan |
| Apr 23b | Miami Vice | Sonny Crockett | Don Johnson |
| Apr 23b | Family Ties | Alex P. Keaton | Michael J. Fox |
| Apr 23b | The Golden Girls | Dorothy Zbornak | Bea Arthur |
| Apr 23b | Hill Street Blues | Capt. Frank Furillo | Daniel J. Travanti |
| Apr 23b | Quantum Leap | Dr. Sam Beckett | Scott Bakula |
| Apr 23b | Dynasty | Alexis Carrington | Joan Collins |
| Apr 25 | The Andy Griffith Show | Sheriff Andy Taylor | Andy Griffith |
| Apr 25 | Columbo | Lt. Columbo | Peter Falk |
| Apr 25 | Hawaii Five-O | Steve McGarrett | Jack Lord |
| Apr 25 | Bewitched | Samantha Stephens | Elizabeth Montgomery |
| Apr 25 | The Twilight Zone | Host/Narrator | Rod Serling |
| Apr 25 | I Love Lucy | Lucy Ricardo | Lucille Ball |
| Apr 26 | Gunsmoke | Marshal Matt Dillon | James Arness |
| Apr 26 | The Mary Tyler Moore Show | Mary Richards | Mary Tyler Moore |
| Apr 26 | The Honeymooners | Ralph Kramden | Jackie Gleason |
| Apr 26 | Taxi | Alex Reiger | Judd Hirsch |
| Apr 26 | Cagney & Lacey | Det. Mary Beth Lacey | Tyne Daly |
| Apr 26 | The Fugitive | Dr. Richard Kimble | David Janssen |
| Apr 28 | Sanford and Son | Fred Sanford | Redd Foxx |
| Apr 28 | The Brady Bunch | Mike Brady | Robert Reed |
| Apr 28 | Knight Rider | Michael Knight | David Hasselhoff |
| Apr 28 | Star Trek (TOS) | Captain James T. Kirk | William Shatner |
| Apr 28 | Dragnet | Sgt. Joe Friday | Jack Webb |
| Apr 28 | The Wonder Years | Kevin Arnold | Fred Savage |
| Apr 29 | Kojak | Lt. Theo Kojak | Telly Savalas |
| Apr 29 | Get Smart | Maxwell Smart (Agent 86) | Don Adams |
| Apr 29 | Frasier | Dr. Frasier Crane | Kelsey Grammer |
| Apr 29 | Star Trek (TOS) | Mr. Spock | Leonard Nimoy |
| Apr 29 | ER | Dr. Doug Ross | George Clooney |
| Apr 29 | Family Matters | Steve Urkel | Jaleel White |
| Apr 30 | Happy Days | Arthur "Fonzie" Fonzarelli | Henry Winkler |
| Apr 30 | Three's Company | Jack Tripper | John Ritter |
| Apr 30 | Seinfeld | Cosmo Kramer | Michael Richards |
| Apr 30 | Charlie's Angels | Jill Munroe | Farrah Fawcett |
| Apr 30 | The Dick Van Dyke Show | Rob Petrie | Dick Van Dyke |
| Apr 30 | Battlestar Galactica (1978) | Commander Adama | Lorne Greene |
| Apr 30b | Perry Mason | Perry Mason | Raymond Burr |
| Apr 30b | Moonlighting | David Addison | Bruce Willis |
| Apr 30b | The Beverly Hillbillies | Jed Clampett | Buddy Ebsen |
| Apr 30b | Barney Miller | Capt. Barney Miller | Hal Linden |
| Apr 30b | The Fresh Prince of Bel-Air | Will Smith | Will Smith |
| Apr 30b | Designing Women | Julia Sugarbaker | Dixie Carter |
| May 1 | The Addams Family | Morticia Addams | Carolyn Jones |
| May 1 | Mork & Mindy | Mork | Robin Williams |
| May 1 | Laverne & Shirley | Laverne DeFazio | Penny Marshall |
| May 1 | The Jeffersons | George Jefferson | Sherman Hemsley |
| May 1 | Murphy Brown | Murphy Brown | Candice Bergen |
| May 1 | Diff'rent Strokes | Arnold Jackson | Gary Coleman |

| May 1v2 | The Dukes of Hazzard | Bo Duke | Tom Wopat |
| May 1v2 | MacGyver | Angus MacGyver | Richard Dean Anderson |
| May 1v2 | The A-Team | Col. Hannibal Smith | George Peppard |
| May 1v2 | Who's the Boss? | Tony Micelli | Tony Danza |
| May 1v2 | 21 Jump Street | Officer Tom Hanson | Johnny Depp |
| May 1v2 | Growing Pains | Dr. Jason Seaver | Alan Thicke |

| May 2 | Bonanza | Ben Cartwright | Lorne Greene |
| May 2 | Friends | Chandler Bing | Matthew Perry |
| May 2 | Saved by the Bell | Zack Morris | Mark-Paul Gosselaar |
| May 2 | The Cosby Show | Cliff Huxtable | Bill Cosby |
| May 2 | Welcome Back, Kotter | Vinnie Barbarino | John Travolta |
| May 2 | NYPD Blue | Det. Andy Sipowicz | Dennis Franz |
| May 3 | Hogan's Heroes | Col. Robert Hogan | Bob Crane |
| May 3 | The Odd Couple | Felix Unger | Tony Randall |
| May 3 | Hart to Hart | Jonathan Hart | Robert Wagner |
| May 3 | Mannix | Joe Mannix | Mike Connors |
| May 3 | Mister Ed | Wilbur Post | Alan Young |
| May 3 | Wings | Joe Hackett | Tim Daly |
| May 4 | The Sopranos | Tony Soprano | James Gandolfini |
| May 4 | Twin Peaks | Special Agent Dale Cooper | Kyle MacLachlan |
| May 4 | Mission: Impossible | Jim Phelps | Peter Graves |
| May 4 | Quincy, M.E. | Dr. R. Quincy | Jack Klugman |
| May 4 | Lost | Dr. Jack Shephard | Matthew Fox |
| May 4 | Cheers | Cliff Clavin | John Ratzenberger |
| May 5 | Gilligan's Island | Gilligan | Bob Denver |
| May 5 | Roseanne | Dan Conner | John Goodman |
| May 5 | China Beach | Colleen McMurphy | Dana Delany |
| May 5 | Home Improvement | Tim Taylor | Tim Allen |
| May 5 | The Nanny | Fran Fine | Fran Drescher |
| May 5 | St. Elsewhere | Dr. Philip Chandler | Denzel Washington |
| May 5v2 | L.A. Law | Michael Kuzak | Harry Hamlin |
| May 5v2 | The Waltons | John-Boy Walton | Richard Thomas |
| May 5v2 | I Dream of Jeannie | Jeannie | Barbara Eden |
| May 5v2 | Newhart | Dick Loudon | Bob Newhart |
| May 5v2 | Starsky & Hutch | Dave Starsky | Paul Michael Glaser |
| May 5v2 | Green Acres | Oliver Wendell Douglas | Eddie Albert |


| May 6 | The Six Million Dollar Man | Col. Steve Austin | Lee Majors |
| May 6 | The Munsters | Herman Munster | Fred Gwynne |
| May 6 | Dr. Quinn, Medicine Woman | Dr. Michaela Quinn | Jane Seymour |
| May 6 | Walker, Texas Ranger | Cordell Walker | Chuck Norris |
| May 6 | CHiPs | Officer Frank "Ponch" Poncherello | Erik Estrada |
| May 6 | Rhoda | Rhoda Morgenstern | Valerie Harper |

| May 7 | ALF | Gordon Shumway / ALF | Paul Fusco (voice/puppet) |
| May 7 | Night Court | Judge Harold "Harry" T. Stone | Harry Anderson |
| May 7 | Full House | Danny Tanner | Bob Saget |
| May 7 | The Incredible Hulk | Dr. David Banner | Bill Bixby |
| May 7 | Good Times | J.J. Evans | Jimmie Walker |
| May 7 | Wonder Woman | Diana Prince / Wonder Woman | Lynda Carter |

---

## 🎨 Arts & Literature Used

| Week | Topic / Question | Answer |
|------|-----------------|--------|
| Apr 23 | Opening line of A Tale of Two Cities | "It was the best of times, it was the worst of times…" |
| Apr 23 | Umberto Eco medieval monastery mystery | The Name of the Rose |
| Apr 23b | Opening line "Call me Ishmael" | Moby-Dick (Melville) |
| Apr 23b | Author of The Great Gatsby | F. Scott Fitzgerald |
| Apr 23b | Poet who wrote "The Road Not Taken" | Robert Frost |
| Apr 23b | Painted The Persistence of Memory (melting clocks) | Salvador Dalí |
| Apr 23b | Detective who lives at 221B Baker Street | Sherlock Holmes (Conan Doyle) |
| Apr 23b | Author of One Hundred Years of Solitude | Gabriel García Márquez |
| Apr 25 | Author of 1984 / Animal Farm | George Orwell |
| Apr 25 | Painter of The Starry Night | Vincent van Gogh |
| Apr 25 | Composer of The Four Seasons | Antonio Vivaldi |
| Apr 25 | Author of Pride and Prejudice | Jane Austen |
| Apr 25 | Three Brontë sister novelists | Charlotte, Emily, Anne |
| Apr 25 | Pulitzer novel — Atticus Finch / Scout | To Kill a Mockingbird (Harper Lee) |
| Apr 26 | Author of The Catcher in the Rye | J.D. Salinger |
| Apr 26 | Painter of "Girl with a Pearl Earring" | Johannes Vermeer |
| Apr 26 | Poet who wrote "The Raven" | Edgar Allan Poe |
| Apr 26 | Pulitzer-winning author of Beloved | Toni Morrison |
| Apr 26 | Russian composer of the 1812 Overture | Pyotr Ilyich Tchaikovsky |
| Apr 26 | Real name behind "Mark Twain" pen name | Samuel Langhorne Clemens |
| Apr 28 | Russian author of War and Peace | Leo Tolstoy |
| Apr 28 | Norwegian painter of The Scream (1893) | Edvard Munch |
| Apr 28 | Author of Brave New World | Aldous Huxley |
| Apr 28 | Composer of Symphony No. 9 / "Ode to Joy" | Ludwig van Beethoven |
| Apr 28 | Pulitzer-winning author of The Old Man and the Sea | Ernest Hemingway |
| Apr 28 | Renaissance artist who painted the Sistine Chapel ceiling | Michelangelo |
| Apr 29 | Author of Frankenstein (1818) | Mary Shelley |
| Apr 29 | Painter of American Gothic | Grant Wood |
| Apr 29 | Beat Gen. author of On the Road | Jack Kerouac |
| Apr 29 | French composer of Boléro | Maurice Ravel |
| Apr 29 | Author of The Lord of the Rings | J.R.R. Tolkien |
| Apr 29 | Italian Renaissance painter of Birth of Venus | Sandro Botticelli |
| Apr 30 | Opening line "Mr. and Mrs. Dursley, of number four, Privet Drive..." | Harry Potter and the Sorcerer's Stone (J.K. Rowling) |
| Apr 30 | Russian author of Crime and Punishment | Fyodor Dostoevsky |
| Apr 30 | Spanish co-founder of Cubism / painter of Guernica | Pablo Picasso |
| Apr 30 | American author of Slaughterhouse-Five | Kurt Vonnegut |
| Apr 30 | Author of memoir I Know Why the Caged Bird Sings | Maya Angelou |
| Apr 30 | French composer of the opera Carmen | Georges Bizet |
| Apr 30b | Spanish author of Don Quixote (first modern novel) | Miguel de Cervantes |
| Apr 30b | Author of The Metamorphosis (Gregor Samsa) | Franz Kafka |
| Apr 30b | Painter of The Kiss (1907–08) | Gustav Klimt |
| Apr 30b | "What happens to a dream deferred?" | Langston Hughes ("Harlem") |
| Apr 30b | Pulitzer-winning author of The Grapes of Wrath | John Steinbeck |
| Apr 30b | Composer of "Eine kleine Nachtmusik" (1787) | Wolfgang Amadeus Mozart |
| May 1 | French Nobel Lit 1957 — author of The Stranger | Albert Camus |
| May 1 | Dickens — 'Please sir, I want some more' | Oliver Twist |
| May 1 | Monet late-career series — water lilies at Giverny | Les Nymphéas / Water Lilies |
| May 1 | Composer of Rhapsody in Blue (1924) | George Gershwin |
| May 1 | Blake poem "Tyger Tyger burning bright" | "The Tyger" |
| May 1 | Mexican self-portrait painter / 'I painted my own reality' | Frida Kahlo |

| May 1v2 | Homer — author of Iliad and Odyssey | Homer (ancient Greek, ~8th c. BC) |
| May 1v2 | Faulkner — As I Lay Dying narrators | 59 narrators |
| May 1v2 | First woman to win Pulitzer for Fiction (1921) | Edith Wharton (The Age of Innocence) |
| May 1v2 | "Do not go gentle into that good night" poet | Dylan Thomas |
| May 1v2 | Rembrandt's famous 1642 painting | The Night Watch |
| May 1v2 | Bach — Brandenburg Concertos (1721) | Johann Sebastian Bach |

| May 2 | Author of Lolita (1955) | Vladimir Nabokov |
| May 2 | Heller's 1961 satirical war novel | Catch-22 |
| May 2 | Painter of the Mona Lisa | Leonardo da Vinci |
| May 2 | Nigerian author of Things Fall Apart (1958) | Chinua Achebe |
| May 2 | Composer of The Rite of Spring (1913) | Igor Stravinsky |
| May 2 | "Whistler's Mother" painter | James McNeill Whistler |
| May 3 | Author of Their Eyes Were Watching God (1937) | Zora Neale Hurston |
| May 3 | Russian-born pioneer of abstract painting | Wassily Kandinsky |
| May 3 | Composer of West Side Story (1957) | Leonard Bernstein |
| May 3 | Author of The Fire Next Time / Go Tell It on the Mountain | James Baldwin |
| May 3 | Italian poet of The Divine Comedy / Inferno | Dante Alighieri |
| May 3 | Spanish Baroque painter of Las Meninas (1656) | Diego Velázquez |
| May 4 | Author of Heart of Darkness (1899) | Joseph Conrad |
| May 4 | Painter of Nighthawks (1942) | Edward Hopper |
| May 4 | Composer of Appalachian Spring / Fanfare for the Common Man | Aaron Copland |
| May 4 | Author of Invisible Man (1952) | Ralph Ellison |
| May 4 | Brontë sister who wrote Wuthering Heights (1847) | Emily Brontë |
| May 4 | French Fauvism founder; "The Dance" | Henri Matisse |
| May 5 | "The Waste Land" (1922) poet | T.S. Eliot |
| May 5 | Author of Les Misérables (1862) | Victor Hugo |
| May 5 | "Because I could not stop for Death" poet | Emily Dickinson |
| May 5 | Author of Ulysses (1922) | James Joyce |
| May 5 | Composer of "From the New World" symphony | Antonín Dvořák |
| May 5 | "Flag" (1955) encaustic painter | Jasper Johns |
| May 5v2 | Oscar Wilde's only novel (aging portrait) | The Picture of Dorian Gray (1890) |
| May 5v2 | Sylvia Plath semi-autobiographical novel (1963) | The Bell Jar |
| May 5v2 | Arthur Miller Pulitzer play about Willy Loman | Death of a Salesman (1949) |
| May 5v2 | French pointillist painter of "La Grande Jatte" | Georges Seurat |
| May 5v2 | Austrian composer of the "Unfinished Symphony" | Franz Schubert |
| May 5v2 | Walt Whitman 1855 poetry collection | Leaves of Grass / "Song of Myself" |


| May 7 | Author of Breakfast at Tiffany's (1958) | Truman Capote |
| May 7 | Composer of "Messiah" (1741) / "Hallelujah" chorus | George Frideric Handel |
| May 7 | Belgian surrealist painter of "The Treachery of Images" | René Magritte |
| May 7 | First Arab Nobel Literature laureate (1988) | Naguib Mahfouz (Egypt) |
| May 7 | Composer of the "Blue Danube" waltz (1866) | Johann Strauss II |
| May 7 | Abstract Expressionist "drip painting" pioneer | Jackson Pollock |

---

## 🧩 General Trivia Topics Used

| Week | Category | Topic/Fact |
|------|----------|-----------|
| Apr 16 | Science | Artemis II — first crewed NASA lunar mission in 50+ years |
| Apr 19 | History | Battles of Lexington and Concord (1775) |
| Apr 19 | History | Bicycle Day / Albert Hofmann / LSD (1943) |
| Apr 19 | History | Grace Kelly married Prince Rainier III (1956) |
| Apr 19 | History | Branch Davidian / Waco siege (1993) |
| Apr 19 | History | Oklahoma City bombing / McVeigh (1995) |
| Apr 19 | History | Salyut 1 / first space station (1971) |
| Apr 20 | History | Robert E. Lee resigned US Army commission (1861) |
| Apr 20 | History | Michael Jordan 63 pts NBA playoff record vs Celtics (1986) |
| Apr 20 | History | Columbine shooting (1999) |
| Apr 20 | History | Danica Patrick first woman to win IndyCar race (2008) |
| Apr 20 | History | Deepwater Horizon explosion (2010) |
| Apr 21 | History | Romulus and Remus found Rome / Natale di Roma (753 BC) |
| Apr 21 | History | Battle of San Jacinto / Texas independence (1836) |
| Apr 21 | History | Red Baron shot down (1918) |
| Apr 21 | History | Seattle World's Fair opened / Space Needle (1962) |
| Apr 21 | History | Geraldo Rivera / Al Capone's vault (1986) |
| Apr 23 | History | First YouTube video uploaded by Jawed Karim (2005) |
| Apr 23 | History | New Coke announcement (1985) |
| Apr 23 | History | Hank Aaron first career home run (1954) |
| Apr 23 | History | Library of Congress established (1800) |
| Apr 20 | Sports | UCLA Bruins won 2026 NCAA Women's Basketball Championship |
| Apr 19 | Sports | UCLA Bruins won 2026 NCAA Women's Basketball Championship |
| Apr 16 | Sports | OKC Thunder #1 seed in West |
| Apr 23b | Science | Human body: adults have 206 bones; babies born with ~270 |
| Apr 23b | Food | Honey never spoils — edible 3000-year-old honey found in Egypt |
| Apr 23b | Myth-bust | Great Wall of China NOT visible from space with naked eye |
| Apr 23b | Animals | Group of flamingos = a "flamboyance" |
| Apr 23b | Geography | Sahara Desert roughly same size as contiguous United States |
| Apr 23b | Animals | Octopuses have three hearts |
| Apr 23b | History | Shortest war: Anglo-Zanzibar War 1896 (38–45 minutes) |
| Apr 23b | TV | The Simpsons — longest-running animated series in US (since 1989) |
| Apr 23b | Food | Worcestershire sauce contains fermented anchovies |
| Apr 23b | Sports | Wayne Gretzky 894 goals / 2,857 career points — untouchable record |
| Apr 25 | Botany | Bananas are berries; strawberries are not |
| Apr 25 | Engineering | Eiffel Tower expands ~6 inches taller in summer |
| Apr 25 | Animals | Group of crows = a 'murder' |
| Apr 25 | History | Cleopatra closer in time to Moon landing than Pyramid construction |
| Apr 25 | Science | Saturn would float in water (lower density) |
| Apr 25 | Etymology | The fruit 'orange' was named first; the color was named after it |
| Apr 25 | Geography | Antarctica is the world's largest desert |
| Apr 25 | Animals | Wombat poop is cube-shaped |
| Apr 25 | Symbols | Statue of Liberty's 7 crown spikes = 7 continents/seas |
| Apr 25 | Language | 'Set' has the most definitions in English (~430+ in OED) |
| Apr 25 | Animals | Sharks predate trees (~450M vs 390M years) |
| Apr 25 | Etymology | Bald eagle 'bald' = old English 'white-headed' |
| Apr 26 | Science | Lightning bolt ~30,000 K — about 5x hotter than the sun's surface |
| Apr 26 | Astronomy | Pluto named by 11-year-old Venetia Burney (1930) |
| Apr 26 | Language | The dot above lowercase i/j is called a "tittle" |
| Apr 26 | Botany | Apples float because they are ~25% air |
| Apr 26 | Geography | Vatican City is the world's smallest country (~109 acres) |
| Apr 26 | Animals | A group of owls is called a "parliament" |
| Apr 26 | Science | Astronauts grow up to 2 inches taller in space |
| Apr 26 | History | Ketchup was sold as medicine in the 1830s |
| Apr 26 | Aviation | Westray–Papa Westray (Scotland) — shortest commercial flight (~90 sec) |
| Apr 26 | Geography | Hawaii is the only US state that commercially grows coffee |
| Apr 26 | Biology | Goosebumps are a vestigial reflex (fur standing up) |
| Apr 26 | Symbols | Scotland's national animal is the unicorn |
| Apr 28 | Science | Bananas slightly radioactive (potassium-40) |
| Apr 28 | Engineering | Eiffel Tower 1,665 steps (674 open to public) |
| Apr 28 | Animals | Jellyfish ~95% water |
| Apr 28 | Science | Mercury — only metal liquid at room temperature |
| Apr 28 | Animals | Group of pandas called an "embarrassment" |
| Apr 28 | Geography | Mariana Trench ~36,000 ft — Everest fits inside |
| Apr 28 | Language | Shakespeare coined ~1,700 English words |
| Apr 28 | Language | Hawaiian alphabet has only 13 letters |
| Apr 28 | Animals | Octopuses have nine brains (1 central + 8 arm) |
| Apr 28 | Culture | More US public libraries than McDonald's |
| Apr 28 | Astronomy | "Blue moon" = 2nd full moon in a calendar month |
| Apr 28 | Animals | Cows have best friends — stressed when separated |
| Apr 28 | Sports | Reds 18-10 — NL Central #1, 4th-best MLB record |
| Apr 28 | Sports | Hurricanes swept Senators (8th straight playoff series) |
| Apr 28 | Sports | Sabres snap NHL-record 14-year postseason drought |
| Apr 28 | Box Office | "Michael" $97M opening (record musical biopic) |
| Apr 29 | Geography | Russia spans 11 time zones — most of any country |
| Apr 29 | Geography | Canada has more lakes than rest of world combined (~2 million) |
| Apr 29 | Geography | Australia (~4,000 km wide) is wider than the Moon's diameter (~3,474 km) |
| Apr 29 | Animals | Sea otters hold hands while sleeping so they don't drift apart |
| Apr 29 | Animals | Tigers have striped skin, not just striped fur |
| Apr 29 | Animals | Snails can sleep up to 3 years if conditions are too dry |
| Apr 29 | Language | A "jiffy" is a real unit of time (~1/100th of a second in physics) |
| Apr 29 | History | Bubble wrap invented 1957 as textured wallpaper before IBM packaging use |
| Apr 29 | Science | A typical cumulus cloud weighs over a million pounds |
| Apr 29 | Food | Heinz ketchup officially leaves the bottle at 0.028 mph |
| Apr 29 | Botany | Pineapple plants take 18-24 months to produce a single fruit |
| Apr 29 | Pop culture | "Wilhelm scream" sound effect used in 400+ films since 1951 |
| Apr 29 | Sports | Reds 19-10 — NL Central #1 |
| Apr 29 | Sports | Spurs first playoff series win since 2017 (4-1 over Trail Blazers) |
| Apr 29 | Sports | NFL Draft: Indiana QB Fernando Mendoza went #1 overall |
| Apr 29 | Box Office | "Michael" trailer 116.2M views in 24h — record for music biopic |
| Apr 30 | Geography | Lake Baikal — world's deepest lake (~5,387 ft); ~20% of Earth's unfrozen freshwater |
| Apr 30 | Science | Teaspoon of neutron-star material weighs ~6 billion tons |
| Apr 30 | Animals | Group of giraffes is a "tower"; group of porcupines a "prickle" |
| Apr 30 | Food | Saffron — most expensive spice; ~75,000 flowers per pound |
| Apr 30 | Language | Pneumonoultramicroscopicsilicovolcanoconiosis (45 letters) — longest word in major dictionaries |
| Apr 30 | Sports | Olympic gold medals are 92.5% silver with ≥6g gold plating |
| Apr 30 | History | Diners Club — first multipurpose charge card (1950) |
| Apr 30 | Etymology | "Avocado" from Nahuatl āhuacatl (testicle) |
| Apr 30 | Animals | Reindeer eyes change color seasonally (gold→blue) |
| Apr 30 | Geography | Caspian Sea — largest enclosed body of water on Earth |
| Apr 30 | Astronomy | Earth's mini-moons / quasi-satellite Kamoʻoalewa |
| Apr 30 | Animals | Shrimp's heart is in its head (cephalothorax) |
| Apr 30b | Biology | Humans share ~50% DNA with bananas |
| Apr 30b | Food | Wasabi at US sushi = horseradish dyed green |
| Apr 30b | Animals | Platypus — one of 5 egg-laying mammal species (monotremes) |
| Apr 30b | Geography | Brazil is only Portuguese-speaking country in South America |
| Apr 30b | History/Food | Cacao beans used as Aztec currency (100 = 1 turkey) |
| Apr 30b | Sports | Table tennis added to Olympics: 1988 Seoul Games |
| Apr 30b | Etymology | "Disaster" from Italian disastro = "bad star" |
| Apr 30b | Animals | Group of cats = clowder; kittens = kindle |
| Apr 30b | Science | Microwave oven invented by accident (Percy Spencer, 1945) |
| Apr 30b | Food | Peanuts are legumes, not actual nuts |
| Apr 30b | Geography | Maine borders only ONE other US state (New Hampshire) |
| Apr 30b | Animals | Only male seahorses become pregnant and give birth |
| Apr 30b | Sports | Reds 19-11, NL Central #1; vs Rockies 12:40 PM ET Apr 30 |
| Apr 30b | Sports | Pistons force Game 6 (Cade Cunningham 45 pts franchise record) |
| Apr 30b | Sports | Flyers advance past Penguins (4-2 series); face Hurricanes Rd 2 |
| Apr 30b | Sports | Canadiens push Lightning to brink 3-2 |
| Apr 30b | Box Office | Michael (MJ biopic) $97M domestic / $217M global — biopic record |
| Apr 30 | Sports | Reds 19-11, NL Central #1; lost 13-2 to Rockies Apr 29 |
| Apr 30 | Sports | Flyers eliminate Penguins 4-2 (1-0 OT in Game 6) |
| Apr 30 | Sports | #1 Pistons trail #8 Magic 3-1 in NBA 1st round |
| Apr 30 | Box Office | "Michael" $97M domestic / $218.7M global opening — biopic record |
| May 1 | Animals | Polar bears have black skin under white fur |
| May 1 | Food | Cheese is most stolen food globally (~4%) |
| May 1 | History/Tech | Nintendo founded 1889 as playing card company |
| May 1 | Biology | Humans and giraffes both have 7 neck vertebrae |
| May 1 | Animals | Butterflies taste with their feet |
| May 1 | History | Netherlands vs. Scilly 335-year war — zero casualties |
| May 1 | Math | More chess games possible than atoms in observable universe |
| May 1 | Geography | Pacific Ocean larger than all land combined |
| May 1 | Science | Penicillin discovered accidentally by Fleming (1928) |
| May 1 | Animals | Vultures = "wake" (feeding) or "committee" (perching) |
| May 1 | Sports | Reds 20-11, NL Central #1; @ Pittsburgh 6:45 PM ET |
| May 1 | Sports | NBA Magic lead Pistons 3-2 (Game 6 tonight) |
| May 1 | Sports | Sabres/Bruins Game 6 tonight (NHL playoffs) |
| May 1 | Box Office | Devil Wears Prada 2 debuting ~$85M domestic / ~$180M global |

| May 1v2 | Science | A day on Venus is longer than a year on Venus |
| May 1v2 | History | Tug of war was an Olympic sport 1900-1920 |
| May 1v2 | Animals | Cats cannot taste sweetness (unique among mammals) |
| May 1v2 | History | Oxford University older than the Aztec Empire |
| May 1v2 | Food | M&M's created 1941 for WWII soldiers |
| May 1v2 | Animals | Penguins propose with pebbles |
| May 1v2 | Travel | Eiffel Tower has its own post office |
| May 1v2 | History | Great Fire of London (1666) — 13K homes, ~6 deaths |
| May 1v2 | Animals | Cockroach survives a week without its head |
| May 1v2 | Geography | Norway has a village called "Å" |
| May 1v2 | History | Fredric Baur (Pringles can inventor) buried in a Pringles can |
| May 1v2 | Science | More possible chess games than atoms in observable universe (already May 1 used) |
| May 2 | Animals | Group of zebras = "dazzle" |
| May 2 | Etymology | Plastic tip on shoelace = "aglet" |
| May 2 | Tech | First eBay sale (Sept 1995): broken laser pointer for $14.83 |
| May 2 | Biology | Lobster blood is colorless; turns blue with oxygen (hemocyanin) |
| May 2 | Geography | Longest place name: NZ hill, 85 letters (Taumatawhakatangihanga…) |
| May 2 | Anatomy | Smallest bone in human body: stapes (ear, ~3mm) |
| May 2 | Animals | Ostrich's eye larger than its brain |
| May 2 | Science | Sharks predate Saturn's rings (450M vs 10–100M years) |
| May 2 | Symbols | Statue of Liberty was copper-colored; oxidation made it green |
| May 2 | Math | "Googol" = 10^100; Google's name was a misspelling |
| May 2 | Sports | Reds 20-13, NL Central #2 (1.0 GB Cubs); lost 17-7 to Pirates May 2 |
| May 2 | Sports | Pirates drew 7 consecutive walks vs Reds — tied MLB record (1909, 1983) |
| May 2 | Sports | Golden Tempo wins Kentucky Derby 23-1; Cherie DeVaux first female trainer to win |
| May 2 | Sports | Sabres beat Bruins 4-1 — first playoff series win since 2007 |
| May 2 | Sports | Knicks dump Hawks 4-2 — only Eastern team into NBA Round 2 so far |
| May 2 | Box Office | Devil Wears Prada 2 #1 — ~$80M opening, ~3x original ($27.5M, 2006) |
| May 3 | Architecture | Burj Khalifa, Dubai (2,717 ft / 828 m) — world's tallest building since 2010 |
| May 3 | Animals | Sloths can hold breath underwater up to 40 minutes |
| May 3 | Animals | Honeybees use 'waggle dance' to communicate food location |
| May 3 | Astronomy | Pluto demoted to dwarf planet by IAU on Aug 24, 2006 |
| May 3 | Botany | Methuselah (Great Basin bristlecone pine, CA) ~4,855 years old |
| May 3 | Food origin | Coffee discovered in Ethiopia (legendary goat herder Kaldi) |
| May 3 | Science | Marie Curie's notebooks still radioactive — lead-lined storage |
| May 3 | Sports | Canada has 2 national sports — lacrosse (summer), hockey (winter) |
| May 3 | Animals | Dolphins use unique 'signature whistles' as names |
| May 3 | Geography | Greenland ~80% ice; Iceland only ~11% ice (names backwards) |
| May 3 | Geography | US-Russia closest distance: 2.4 mi (Diomede Islands) |
| May 3 | Etymology | '@' symbol = 'arroba' in Spanish/Portuguese (~25 lb unit) |
| May 3 | Sports | Reds 20-13, NL Central #2 (2 GB Cubs); 76ers 3-1 comeback over Celtics |
| May 3 | Sports | Golden Tempo wins Kentucky Derby — Cherie DeVaux 1st female trainer |
| May 3 | Box Office | Devil Wears Prada 2 #1 — ~$75-80M domestic / $180M global |
| May 4 | History | Cleopatra was Greek (Ptolemaic), not Egyptian |
| May 4 | Geography | Sudan has more pyramids than Egypt (~250 vs ~120) |
| May 4 | Acronym | ZIP code = Zone Improvement Plan (USPS 1963) |
| May 5 | History | Cinco de Mayo = Battle of Puebla 1862 (NOT Mexican Independence Day — that's Sep 16) |
| May 5 | Animals | Group of sharks = "shiver" |
| May 5 | Food | Carrots originally purple; Dutch cultivated orange in 17th c. for House of Orange |
| May 5 | Language | "Salary" from Latin salarium — Romans paid in/for salt |
| May 5 | Engineering | First Ferris wheel — 1893 Chicago World's Fair, George Ferris |
| May 5 | Animals | Crows recognize individual human faces and hold grudges for years |
| May 5 | Geography | Amazon River = more freshwater than next 7 largest rivers combined |
| May 5 | Science | Lightning strikes Earth ~100 times/second (~8.6M times/day) |
| May 5 | Animals | Flamingo can only eat with head upside down |
| May 5 | Astronomy | More stars in observable universe than grains of sand on all Earth's beaches |
| May 5 | Sports | Reds 20-14; @ Cubs (Wrigley) 7:40 PM ET; Wembanyama 12-block NBA Playoff record |
| May 5 | Sports | Kentucky Derby: Golden Tempo 23-1; Cherie DeVaux first female trainer to win |
| May 5 | Sports | 76ers beat Celtics in Game 7; Knicks blowout 76ers 137-98 Game 1 Conf. Semis |
| May 5 | Box Office | Devil Wears Prada 2 — $77M domestic / $233.6M global; Meryl Streep biggest opening ever |
| May 5v2 | Geography | Monaco most densely populated country (~19,000/km²) |
| May 5v2 | Language | "Typewriter" typed using only QWERTY top row |
| May 5v2 | Animals | Honey badger = Guinness World's Most Fearless Animal |
| May 5v2 | History | Eiffel Tower scheduled for demolition 1909; saved by radio use |
| May 5v2 | Science | Mpemba effect: hot water can freeze faster than cold |
| May 5v2 | Pop Culture | Mel Blanc (Bugs Bunny) allergic to carrots |
| May 5v2 | Animals | Group of hippos = bloat |
| May 5v2 | Cards | King of Hearts only king without a mustache (Suicide King) |
| May 5v2 | Science | Scoville Scale invented by Wilbur Scoville 1912 |
| May 5v2 | Animals | Queen ants can live up to 30 years |
| May 4 | Geography | Mauna Kea — tallest mountain base-to-peak (~33,500 ft) |
| May 4 | Botany | Cashews grow on outside of fruit; shell has urushiol like poison ivy |
| May 4 | Art | Van Gogh sold one painting in life — The Red Vineyard |
| May 4 | Animals | Blue whale heart ~400 lbs (size of small car) |
| May 4 | Animals | Snails ~14,000 microscopic teeth (radula) |
| May 4 | History | Olympic flame lit by parabolic mirror at ancient Olympia |
| May 4 | Astronomy | Venus hottest planet (~864°F), not Mercury — CO2 atmosphere |
| May 4 | Science | First heart transplant — Dr. Christiaan Barnard, Cape Town, Dec 3 1967 |
| May 4 | Language | Letter Q absent from all 50 US state names |
| May 4 | Sports | Reds 20-14, NL Central #2 (2 GB); swept 0-3 by Pirates |
| May 4 | Sports | NHL Round 2: Hurricanes 3-0 Flyers; Avalanche 9-6 Wild |
| May 4 | Sports | NBA Round 1 closeout: Cavs/Pistons/76ers all win Game 7s (Det/Phi 3-1 comebacks); Knicks 51-pt Game 6 win franchise record |
| May 4 | Sports | NFL Draft: Rams shock w/ QB Ty Simpson #13 despite reigning MVP |
| May 4 | Sports | MLS: Vancouver Whitecaps best-ever start; Orlando 4-3 over Inter Miami |
| May 4 | Box Office | Devil Wears Prada 2 final opening: $77M dom / $233.6M global — Streep's best opener |


| May 7 | Animals | Mantis shrimp has 16 color photoreceptor types (humans have 3) |
| May 7 | Science | Sound travels ~4x faster in water than air |
| May 7 | History | Alaska purchased from Russia for $7.2M in 1867 (Seward's Folly) — <2 cents/acre |
| May 7 | Science | Photon takes ~100,000 years sun core→surface; only 8 min to reach Earth |
| May 7 | Animals | Elephants (and hippos) cannot jump |
| May 7 | Food | Vanilla from Vanilla planifolia orchid seed pods; originally from Mexico |
| May 7 | Language | "Robot" coined by Czech playwright Karel Čapek in R.U.R. (1920) |
| May 7 | Tech | First computer "bug" — real moth in Harvard Mark II relay, Grace Hopper team, 1947 |
| May 7 | Geography | Lake Superior = world's largest freshwater lake by surface area (~31,700 sq mi) |
| May 7 | History | Napoleon was ~5'7" — average for his era; "short" myth = British propaganda + unit confusion |
| May 7 | Sports | Reds 21-16, NL Central 2nd (3 GB Cubs 24-12); beat Tampa Bay Rays 12-6 (Elly De La Cruz 2 HR) |
| May 7 | Sports | NBA Conf. Semis: Cavs/Pistons G2, Nuggets/Wolves G2, Lakers/Thunder G2 |
| May 7 | Sports | NHL Round 2: Hurricanes lead Flyers 3-0; Canadiens eliminated Lightning in 7 |
| May 7 | Box Office | Devil Wears Prada 2 — $77M/$233.6M global; Mortal Kombat II opening this weekend |

---

## 📅 History Dates Covered

| Week | Calendar Date Used for "This Day in History" |
|------|----------------------------------------------|
| Apr 16 | April 16 |
| Apr 19 | April 19 |
| Apr 20 | April 20 |
| Apr 21 | April 21 |
| Apr 23 | April 23 |
| Apr 23b | April 23 (alt events: Shakespeare born 1564, Buchanan born 1791, NABBP founded 1871) |
| Apr 25 | April 25 (ANZAC/Gallipoli 1915, DNA helix 1953, Hubble deployed 1990, Ella Fitzgerald born 1917) |
| Apr 26 | April 26 (Chernobyl 1986, Mandela/SA election 1994, Salk vaccine trials 1954, Sybil Ludington 1777) |
| Apr 28 | April 28 (Mutiny on the Bounty 1789, Kon-Tiki sets sail 1947, Muhammad Ali refused induction 1967) |
| Apr 29 | April 29 (Liberation of Dachau 1945, LA Riots 1992, Royal Wedding William & Kate 2011) |
| Apr 30 | April 30 (Washington's inauguration 1789, Louisiana Purchase 1803, Fall of Saigon 1975, Ellen comes out 1997) |
| Apr 30b | April 30 alt: CERN makes WWW public domain 1993; Hitler dies 1945; Louisiana becomes 18th state 1812 |
| May 1 | May 1 (Penny Black 1840, Empire State Building 1931, U-2 spy plane 1960, Bin Laden 2011) |

| May 1v2 | May 1 (alt events: Acts of Union 1707, Citizen Kane 1941, Elvis wedding 1967) |
| May 2 | May 2 (King James Bible 1611, Anne Boleyn arrested 1536, Hungary border fence dismantled 1989) |
| May 3 | May 3 (Thatcher elected UK PM 1979, OKC F5 tornado record 301mph 1999, first spam email 1978, Madeleine McCann disappeared 2007, Penn med school founded 1765) |
| May 4 | May 4 (Manhattan purchase 1626, Kent State 1970, First Grammys 1959, Coral Sea 1942) |
| May 6 | May 6 (Hindenburg 1937, Bannister 4-min mile 1954, iMac unveiled 1998) |
| May 6 | Thornton Wilder's Pulitzer play set in Grover's Corners, NH | Our Town (1938) |
| May 6 | 1948 painting of woman crawling toward farmhouse | Christina's World — Andrew Wyeth |
| May 6 | Chilean poet, Nobel Lit 1971 | Pablo Neruda |
| May 6 | Author of A Streetcar Named Desire (1947) | Tennessee Williams |
| May 6 | Arthur Miller 1953 play / McCarthyism allegory | The Crucible (Salem witch trials) |
| May 6 | Hungarian Romantic composer of Hungarian Rhapsodies | Franz Liszt |

| May 7 | May 7 (Lusitania 1915, Germany WWII surrender 1945, Beethoven 9th premiere 1824) |

---

## 🎉 National Days Featured

| Week | National Days |
|------|--------------|
| Apr 16 | World Voice Day · National Healthcare Decisions Day · International Pizza Cake Day · National Ask an Atheist Day · Day of the Mushroom |
| Apr 19 | National Bicycle Day · National Garlic Day · National Chicken Parmesan Day · National Amaretto Day · Go Fly a Kite Day |
| Apr 20 | National Cheddar Fries Day · National Cold Brew Day · National Look Alike Day · National Pineapple Upside-Down Cake Day · Lima Bean Respect Day |
| Apr 21 | World Creativity Innovation Day · National Kindergarten Day · National Tea Day · National Library Workers Day · Bulldogs Are Beautiful Day |
| Apr 23 | World Book Day · National Picnic Day · National Cherry Cheesecake Day · St. George's Day · National Talk Like Shakespeare Day |
| Apr 23b | National Take a Chance Day · National Lover's Day · English Language Day (UN) · Impossible Astronaut Day |
| Apr 25 | World Penguin Day · National Telephone Day · National Hairstylist Appreciation Day · National Zucchini Bread Day · National Herb Day |
| Apr 26 | National Pretzel Day · Alien Day (4/26 = LV-426) · World Intellectual Property Day · National Help a Horse Day · World Pinhole Photography Day |
| Apr 28 | National Superhero Day · Pay It Forward Day · National Blueberry Pie Day · World Day for Safety & Health at Work · Save the Frogs Day |
| Apr 29 | International Dance Day · National Zipper Day · World Wish Day · National Peace Rose Day · Denim Day · International Guide Dog Day |
| Apr 30 | International Jazz Day · National Honesty Day · Adopt a Shelter Pet Day · National Bubble Tea Day · Bugs Bunny Day · National Animal Advocacy Day
| Apr 30b | National Oatmeal Cookie Day · National Raisin Day · World Veterinary Day · International Jazz Day · National Honesty Day |
| May 1 | International Workers'/May Day · National Lei Day · Loyalty Day · National Chocolate Parfait Day · Mother Goose Day · Global Love Day |

---
| May 1v2 | International Workers' Day · National Space Day · Law Day · School Lunch Hero Day · National Chocolate Parfait Day · National Loyalty Day |
| May 2 | Kentucky Derby Day · National Truffle Day · National Play Outside Day · National Scrapbook Day · World Labyrinth Day · National Homebrew Day · International Female Ride Day |
| May 3 | World Press Freedom Day · National Chocolate Custard Day · Lemonade Day · Wild Koala Day · Garden Meditation Day · International Bereaved Mother's Day |
| May 4 | Star Wars Day (May the 4th) · International Firefighters' Day · National Day of Reason · National Renewal Day · National Golf Day · National Orange Juice Day |
| May 5 | Cinco de Mayo 🌮 · National Cartoonists Day · National Concert Day · International Midwives Day · Museum Lover's Day |
| May 6 | National Nurses Day · National Beverage Day · National Crêpes Suzette Day · International No Diet Day · Coronation Day (UK) |

---
| May 7 | National Day of Reason · Children's Mental Health Awareness Day · National Roast Leg of Lamb Day · National Tourism Day |

---

## ⚙️ Founded & Invented Used

| Week | Subject | Key Fact |
|------|---------|---------|
| Apr 25 | Velcro | Invented 1941 by George de Mestral |
| Apr 25 | Band-Aid | Invented 1920 by Earle Dickson |
| Apr 25 | McDonald's | Founded 1940 |
| Apr 25 | Post-it Note | Adhesive discovered 1968, product launched 1980 |
| Apr 25 | Barcode scanner | First retail use 1974, Juicy Fruit gum |
| Apr 25 | Netflix | Founded 1997 as DVD-by-mail |
| Apr 26 | Coca-Cola | Invented 1886 by John Pemberton |
| Apr 26 | LEGO | Founded 1932 by Ole Kirk Christiansen |
| Apr 26 | Microwave oven | Invented 1945 by Percy Spencer |
| Apr 26 | Amazon | Founded 1994 by Jeff Bezos |
| Apr 26 | Zipper | Patented 1917 by Gideon Sundbäck |
| Apr 26 | Nintendo | Founded 1889 as playing card company |
| Apr 28 | Duct tape | Invented 1943 for US Army |
| Apr 28 | Google | Founded 1998 by Page and Brin |
| Apr 28 | Aspirin | Developed 1897 at Bayer |
| Apr 28 | IKEA | Founded 1943 by 17-year-old Ingvar Kamprad |
| Apr 28 | Bubble Wrap | Invented 1957 as failed wallpaper |
| Apr 28 | FedEx | Founded 1971 by Fred Smith |
| Apr 29 | Scotch tape | Invented 1930 by Richard Drew at 3M |
| Apr 29 | Starbucks | Founded 1971 in Seattle |
| Apr 29 | Sony | Founded 1946 in Tokyo |
| Apr 29 | Ballpoint pen | Patented 1938 by László Bíró |
| Apr 29 | Airbnb | Founded 2008 in San Francisco |
| Apr 30 | Jeans / Levi's | Patented 1873 by Levi Strauss & Jacob Davis |
| Apr 30 | Super Glue | Discovered 1942 by accident |
| Apr 30 | Apple (company) | Founded April 1, 1976 |
| Apr 30 | SPAM | Introduced 1937 by Hormel |
| Apr 30 | Uber | Founded 2009 |
| Apr 30 | Toilet paper roll | Patented 1891 by Seth Wheeler |

## 🏭 Founded & Invented Used

| Week | Question | Answer |
|------|----------|--------|
| May 1v2 | Twitter (X) founded year | 2006 (Dorsey, Glass, Stone, Williams) |
| May 1v2 | Telephone inventor and year | Alexander Graham Bell, 1876 |
| May 1v2 | Google founded year | 1998 (Page & Brin, Menlo Park garage) |
| May 1v2 | World Wide Web inventor and location | Tim Berners-Lee, 1989, CERN |
| May 1v2 | LEGO founded year and country | 1932, Denmark (Ole Kirk Christiansen) |
| May 1v2 | First iPhone sale year | 2007 (June 29) |
| May 2 | Walmart founded year/founder | 1962, Sam Walton (Rogers, AR) |
| May 2 | Walt Disney Company founded year | 1923 (Walt & Roy Disney) |
| May 2 | Microsoft founded year/founders | 1975, Bill Gates & Paul Allen |
| May 2 | Polaroid instant camera inventor | Edwin Land (1947 demo, 1948 sale) |
| May 2 | Frisbee inventor | Walter Frederick Morrison (1957); Wham-O trademark 1959 |
| May 2 | Slinky inventor and year | Richard James, 1943 |
| May 3 | Ford Motor Company founded year | 1903 (Henry Ford, Detroit) |
| May 3 | Hershey's chocolate founder/year | Milton Hershey, 1894 |
| May 3 | Wikipedia launch date | January 15, 2001 (Jimmy Wales & Larry Sanger) |
| May 3 | Crayola crayons introduced | 1903 (Binney & Smith), original 8-pack 5¢ |
| May 3 | Tetris inventor | Alexey Pajitnov, 1984 (Soviet Union) |
| May 3 | Kleenex original use (1924) | Removing cold cream / makeup |
| May 4 | Boeing founded year/place | 1916, Seattle (William Boeing) |
| May 4 | Air conditioning inventor/year | Willis Carrier, 1902 (Brooklyn print shop) |
| May 4 | Pepsi-Cola original name | "Brad's Drink" (Caleb Bradham, 1893) |
| May 4 | Kellogg's founder/year | W.K. Kellogg, 1906 (Battle Creek, MI) |
| May 4 | Facebook founded | 2004, Mark Zuckerberg, Harvard dorm |
| May 4 | Disneyland opened | July 17, 1955 (Anaheim, CA) |
| May 5 | YouTube founded year/founders | 2005, Hurley/Chen/Karim |
| May 5 | Instagram acquisition price/employees | $1B by Facebook, 2012; only 13 employees |
| May 5 | Play-Doh original use | Wallpaper-cleaning compound (1950s) |
| May 5 | Rubik's Cube inventor/year | Ernő Rubik, 1974 |
| May 5 | SpaceX founded year/founder | 2002, Elon Musk |
| May 5 | Pixar spun off from/sold to | Lucasfilm → Steve Jobs ($5M, 1986) |
| May 5v2 | Nike original name (1964) | Blue Ribbon Sports (Phil Knight & Bill Bowerman) |
| May 5v2 | eBay founded year / first sale | 1995 / broken laser pointer $14.83 (Pierre Omidyar) |
| May 5v2 | Gatorade invented for which university (1965) | University of Florida (the Gators) |
| May 5v2 | WD-40 meaning / year | Water Displacement 40th formula / 1953 (Norm Larsen) |
| May 5v2 | Teflon / PTFE accidental discoverer (1938) | Roy Plunkett (DuPont) |
| May 5v2 | Reddit founded year / university | 2005 / University of Virginia (Huffman & Ohanian) |
| May 6 | CNN founded year/founder | 1980 / Ted Turner, Atlanta |
| May 6 | Listerine original use (1879) | Surgical antiseptic; rebranded for bad breath 1914 |
| May 6 | Snapchat founder/year | Evan Spiegel, 2011, Stanford |
| May 6 | Monopoly sold to Parker Brothers year | 1935 (based on Elizabeth Magie's 1903 Landlord's Game) |
| May 6 | H.J. Heinz Company founded | 1869 by Henry John Heinz, Pittsburgh |
| May 6 | LinkedIn co-founder | Reid Hoffman, launched May 2003 |


| May 7 | Atari founded year/founders | 1972, Nolan Bushnell & Ted Dabney, Sunnyvale CA |
| May 7 | Eiffel Tower designer / built for | Gustave Eiffel / 1889 Paris World's Fair |
| May 7 | American Red Cross founded | 1881, Clara Barton, Washington D.C. |
| May 7 | Harley-Davidson founded year/city | 1903, Milwaukee WI (Harley & Davidson) |
| May 7 | ARPANET first message (1969) | "LO" (crashed during "LOGIN"); UCLA to Stanford, Oct 29 1969 |
| May 7 | UPS founded year/founder/city | 1907, James Casey, Seattle WA |

---

## 🎵 Music Used (1990–2010)

| Week | Song | Artist | Year |
|------|------|--------|------|
| May 3 | Smells Like Teen Spirit | Nirvana | 1991 |
| May 3 | Wonderwall | Oasis | 1995 |
| May 3 | ...Baby One More Time | Britney Spears | 1998 |
| May 3 | Hey Ya! | OutKast | 2003 |
| May 3 | Rolling in the Deep | Adele | 2010 |
| May 5v2 | Lose Yourself | Eminem | 2002 |
| May 5v2 | Beautiful Day | U2 | 2000 |
| May 5v2 | Crazy in Love | Beyoncé | 2003 |
| May 5v2 | Complicated | Avril Lavigne | 2002 |
| May 5v2 | In Da Club | 50 Cent | 2003 |
| May 6 | I Will Always Love You | Whitney Houston | 1992 |
| May 6 | Losing My Religion | R.E.M. | 1991 |
| May 6 | Seven Nation Army | The White Stripes | 2003 |
| May 6 | Yeah! | Usher ft. Lil Jon & Ludacris | 2004 |
| May 6 | Umbrella | Rihanna | 2007 |
| May 6 | Mr. Brightside | The Killers | 2003 |

---
| May 7 | Waterfalls | TLC | 1995 |
| May 7 | Under the Bridge | Red Hot Chili Peppers | 1992 |
| May 7 | My Heart Will Go On | Céline Dion | 1997 |
| May 7 | Creep | Radiohead | 1992 |
| May 7 | Viva la Vida | Coldplay | 2008 |
| May 7 | Fallin' | Alicia Keys | 2001 |

---

| May 6 | Capital of Ohio | Columbus |
| May 6 | Capital of Sweden | Stockholm |
| May 6 | Capital of Cuba | Havana |
| May 6 | Capital of Washington (state) | Olympia |

| May 7 | Capital of Minnesota | St. Paul |
| May 7 | Capital of Turkey | Ankara |
| May 7 | Capital of Bolivia | Sucre (constitutional) / La Paz (seat of government) |
| May 7 | Capital of Ukraine | Kyiv |
| May 7 | Capital of Belgium | Brussels |

| May 7v2 | Capital of Virginia | Richmond |
| May 7v2 | Capital of Hungary | Budapest |
| May 7v2 | Capital of Alaska | Juneau |
| May 7v2 | Capital of Pakistan | Islamabad |

| May 7v2 | The Flintstones | Fred Flintstone | Alan Reed (voice) |
| May 7v2 | Lou Grant | Lou Grant | Ed Asner |
| May 7v2 | Wiseguy | Vinnie Terranova | Ken Wahl |
| May 7v2 | In the Heat of the Night | Chief Virgil Tibbs | Howard Rollins |
| May 7v2 | Picket Fences | Sheriff Jimmy Brock | Tom Skerritt |
| May 7v2 | Homicide: Life on the Street | Det. Frank Pembleton | Andre Braugher |

| May 7v2 | Alice Walker — The Color Purple (1982), Pulitzer 1983 | Alice Walker |
| May 7v2 | Piet Mondrian — De Stijl founder, primary colors + grid | Piet Mondrian |
| May 7v2 | "Clair de Lune" composer (Suite bergamasque, 1905) | Claude Debussy |
| May 7v2 | Author of Walden (1854), lived alone at Walden Pond | Henry David Thoreau |
| May 7v2 | Author of My Ántonia (1918), Nebraska pioneer life | Willa Cather |
| May 7v2 | "School of Athens" fresco (1509-11) in Vatican | Raphael |

| May 7v2 | Kodak founded year/founder | 1892, George Eastman, Rochester NY |
| May 7v2 | Nylon — first synthetic fabric inventor/year | Wallace Carothers, DuPont, 1935 |
| May 7v2 | Tupperware inventor/year | Earl Tupper, 1946 |
| May 7v2 | General Motors founded year/city | 1908, Flint MI (William Durant) |
| May 7v2 | Kevlar inventor/year/company | Stephanie Kwolek, 1965, DuPont |
| May 7v2 | Campbell Soup Company founded | 1869, Camden NJ (Joseph Campbell) |

| May 7v2 | Animals | Dolphins sleep with one eye open (unihemispheric sleep) |
| May 7v2 | Science | Photo 51 — Rosalind Franklin's 1952 X-ray that revealed DNA double helix |
| May 7v2 | Food | Chocolate melts at ~93°F (34°C) — just below body temp |
| May 7v2 | Language | "Serendipity" coined 1754 by Horace Walpole (Serendip = Sri Lanka) |
| May 7v2 | Animals | Group of pigs = sounder |
| May 7v2 | History | Colosseum completed 80 AD — held 50,000–80,000 spectators |
| May 7v2 | Science/Tech | First webcam (1991) watched a coffee pot at Cambridge University |
| May 7v2 | Animals | Pistol shrimp snap creates ~8,000°F cavitation bubble |
| May 7v2 | Food | First breakfast cereal: Granula (1863), James Caleb Jackson |
| May 7v2 | Botany | Sunflower head = up to 2,000 individual florets |
| May 7v2 | Sports | Reds 20-17, L6, 5th in NL Central, 5.0 GB Cubs; @ Cubs 2:20 PM ET |
| May 7v2 | Sports | NHL: Hurricanes 3-0 over Flyers (R2), Canadiens eliminated Lightning in 7 |
| May 7v2 | Sports | NBA: Spurs tie Timberwolves 1-1 (133-95 G2); Knicks 2-0 over 76ers |
| May 7v2 | Box Office | Devil Wears Prada 2 — $77M dom/$233.6M global; Mortal Kombat II opens this wknd |

| May 7v2 | Zombie | The Cranberries | 1994 |
| May 7v2 | Smooth (feat. Rob Thomas) | Santana | 1999 |
| May 7v2 | You Oughta Know | Alanis Morissette | 1995 |
| May 7v2 | Boulevard of Broken Dreams | Green Day | 2004 |
| May 7v2 | Gold Digger (feat. Jamie Foxx) | Kanye West | 2005 |
| May 7v2 | Poker Face | Lady Gaga | 2008 |

| May 7v2 | May 7 alt history: Joan of Arc raises Siege of Orléans (1429); Tchaikovsky born (1840); AMA founded (1847) | — |
| May 7v2 | National Days: World Password Day, National Packaging Design Day, Cosmopolitan Day | — |


| May 8 | Capital of New York State | Albany |
| May 8 | Capital of Illinois | Springfield |
| May 8 | Capital of Japan | Tokyo |
| May 8 | Capital of Ghana | Accra |
| May 8 | Capital of the Netherlands | Amsterdam |

| May 8 | The Avengers (UK 1965–68) | Emma Peel | Diana Rigg |
| May 8 | The Streets of San Francisco | Det. Steve Keller | Michael Douglas |
| May 8 | Emergency! | John Gage | Randolph Mantooth |
| May 8 | The Love Boat | Capt. Merrill Stubing | Gavin MacLeod |
| May 8 | Soap | Jodie Dallas | Billy Crystal |
| May 8 | Eight is Enough | Tom Bradford | Dick Van Patten |

| May 8 | Best-selling mystery novelist of all time | Agatha Christie (2B+ books) |
| May 8 | Andy Warhol Campbell's Soup Cans (1962) movement | Pop Art |
| May 8 | Georgia O'Keeffe — "Mother of American Modernism" | American modernist; flower series & NM landscapes |
| May 8 | Beckett's play about waiting | Waiting for Godot (1953) |
| May 8 | Italian composer of La Traviata, Aida, Otello | Giuseppe Verdi |
| May 8 | John Milton epic poem 1667 — Fall of Man | Paradise Lost |

| May 8 | ESPN founded year/city | 1979, Bristol CT (Bill Rasmussen) |
| May 8 | Windshield wiper inventor/year | Mary Anderson, 1903 |
| May 8 | Shopping cart inventor/year/city | Sylvan Goldman, 1937, Oklahoma City |
| May 8 | Subway founded year/founder's age | 1965, Fred DeLuca (age 17), Bridgeport CT |
| May 8 | Adidas founder / Puma connection | Adolf "Adi" Dassler 1949; brother Rudolf founded Puma |
| May 8 | Safety pin inventor/year | Walter Hunt, 1849 |

| May 8 | Etymology | Petrichor — smell of rain (coined 1964, Bear & Thomas) |
| May 8 | Animals | Group of ferrets = "business" |
| May 8 | Biology | Koala fingerprints nearly indistinguishable from human |
| May 8 | History/Humor | Oldest recorded joke (~1900 BC Sumerian) is a fart joke |
| May 8 | Science | Human nose detects ~1 trillion distinct smells |
| May 8 | Etymology | "Muscle" from Latin musculus = "little mouse" |
| May 8 | Nature | Great Barrier Reef = world's largest living structure (~1,400 mi) |
| May 8 | History/Architecture | Pentagon has 2x bathrooms needed — Virginia segregation law |
| May 8 | Animals | Honey bees beat wings ~200x/second (creates the buzz) |
| May 8 | Physics | Remove atomic empty space — all humanity fits in a sugar cube |
| May 8 | Sports | Reds 20-18, L7, NL Central 5th (6 GB Cubs); vs Houston Astros 6:10 PM ET |
| May 8 | Sports | NBA R2: Pistons 2-0 Cavs; Knicks 2-0 76ers; Thunder 1-0 Lakers; Wolves/Spurs 1-1 |
| May 8 | Sports | NHL R2: Canes 2-0 Flyers; Sabres 1-0 Canadiens (G2 tonight); Avs 2-0 Wild; VGK/Ducks 1-1 |
| May 8 | Sports | Kentucky Derby: Golden Tempo 23-1; Cherie DeVaux first female trainer to win |
| May 8 | Box Office | Devil Wears Prada 2 — $77M dom/$233.6M global (Meryl Streep biggest-ever opener) |

| May 8 | No Scrubs | TLC | 1999 |
| May 8 | Toxic | Britney Spears | 2003 |
| May 8 | Numb | Linkin Park | 2003 |
| May 8 | Since U Been Gone | Kelly Clarkson | 2004 |
| May 8 | Irreplaceable | Beyoncé | 2006 |
| May 8 | Fix You | Coldplay | 2005 |

| May 8 | May 8 (VE Day 1945, Smallpox eradicated 1980, Coca-Cola first sold 1886) | — |
| May 8 | National Days: World Red Cross Day, National No Socks Day, National Teacher Appreciation Day, National Coconut Cream Pie Day | — |


| May 11 | Capital of Pennsylvania | Harrisburg |
| May 11 | Capital of Spain | Madrid |
| May 11 | Capital of Tanzania | Dodoma |
| May 11 | Capital of Nevada | Carson City |

| May 11 | The West Wing | President Josiah "Jed" Bartlet | Martin Sheen |
| May 11 | Lost in Space (1965) | Dr. Zachary Smith | Jonathan Harris |
| May 11 | The Bionic Woman | Jaime Sommers | Lindsay Wagner |
| May 11 | Adam-12 | Officer Pete Malloy | Martin Milner |
| May 11 | Buffy the Vampire Slayer | Buffy Summers | Sarah Michelle Gellar |
| May 11 | Ally McBeal | Ally McBeal | Calista Flockhart |

| May 11 | French novelist of Madame Bovary (1857) | Gustave Flaubert |
| May 11 | Composer of Peter and the Wolf (1936) | Sergei Prokofiev |
| May 11 | Painter of Le Déjeuner sur l'herbe (1863) and Olympia (1865) | Édouard Manet |
| May 11 | Canadian author of The Handmaid's Tale (1985) | Margaret Atwood |
| May 11 | French painter of Liberty Leading the People (1830) | Eugène Delacroix |
| May 11 | Author of Native Son (1940) | Richard Wright |

| May 11 | Toyota founded year/founder | 1937, Kiichiro Toyoda (Japan) |
| May 11 | Tesla, Inc. founded year/founders | 2003, Martin Eberhard & Marc Tarpenning (Musk joined 2004) |
| May 11 | Spotify founded year/founders | 2006, Daniel Ek & Martin Lorentzon, Sweden |
| May 11 | Wendy's founded year/founder/city | 1969, Dave Thomas, Columbus OH |
| May 11 | PayPal founded year / original name | 1998 / Confinity (merged X.com 2000, rebranded 2001) |
| May 11 | Ferrari founded year / city | 1939, Maranello, Italy (Enzo Ferrari) |

| May 11 | Animals | Hummingbirds — only birds capable of true backwards flight; wings 50–80 beats/sec |
| May 11 | Animals | Hippos secrete reddish-pink hipposudoric acid as natural sunscreen + antibiotic |
| May 11 | Religion/Tech | Vatican has world's only Latin-language ATM |
| May 11 | Engineering | Niagara Falls American side "turned off" 1969 by US Army Corps to study erosion |
| May 11 | Animals | Cheetah ~70 mph (113 km/h) — fastest land animal but overheats quickly |
| May 11 | Art | Mona Lisa has no eyebrows or eyelashes |
| May 11 | Geography | Iceland has no mosquitoes |
| May 11 | Pop culture | Buzz Aldrin's mother's maiden name was Marion Moon |
| May 11 | Science | Microsoft anechoic chamber in Redmond — world's quietest room (-20.6 dBA) |
| May 11 | Geography | Saudi Arabia imports camels from Australia (~1M feral in Outback) |
| May 11 | Engineering | Great Pyramid of Giza tallest man-made structure for ~3,800 years |
| May 11 | Astronomy | ISS astronauts see ~16 sunrises every 24 hours (90-min orbit) |
| May 11 | Sports | Reds 22-19, .537, T-4th NL Central (5 GB Cubs); swept Astros 3-0; no game today |
| May 11 | Sports | NBA R2: Knicks SWEEP 76ers (2nd straight ECF); Thunder 3-0 Lakers; Cavs cut Pistons series to 2-1; Wolves tie Spurs 2-2 |
| May 11 | Sports | NHL R2: Hurricanes SWEEP Flyers; Sabres/Habs 1-1; Avs 2-1 Wild; VGK 2-1 Ducks |
| May 11 | Sports | NCAA: Wake Forest vs Syracuse to play 2027 opener at BMO Field, Toronto (first NCAA football in Canada) |
| May 11 | Box Office | Devil Wears Prada 2 holds #1 (2nd wknd ~$32M) over Mortal Kombat II ($40M dom / $63M global open) |

| May 11 | I Want It That Way | Backstreet Boys | 1999 |
| May 11 | Black Hole Sun | Soundgarden | 1994 |
| May 11 | Don't Speak | No Doubt | 1995 |
| May 11 | Hot in Herre | Nelly | 2002 |
| May 11 | Single Ladies (Put a Ring on It) | Beyoncé | 2008 |
| May 11 | Bad Romance | Lady Gaga | 2009 |

| May 11 | May 11 (Bob Marley dies 1981; Deep Blue beats Kasparov 1997; Academy of Motion Picture Arts founded 1927; Minnesota 32nd state 1858) | — |
| May 11 | National Days: National Eat What You Want Day, National Twilight Zone Day, National Women's Checkup Day, Vietnam Human Rights Day | — |


| May 12 | Capital of Missouri | Jefferson City |
| May 12 | Capital of Romania | Bucharest |
| May 12 | Capital of Massachusetts | Boston |
| May 12 | Capital of Kenya | Nairobi |

| May 12 | Rawhide | Rowdy Yates | Clint Eastwood |
| May 12 | The Wild Wild West | James T. West | Robert Conrad |
| May 12 | The Mod Squad | Pete Cochran | Michael Cole |
| May 12 | Falcon Crest | Angela Channing | Jane Wyman |
| May 12 | Beverly Hills, 90210 | Brandon Walsh | Jason Priestley |
| May 12 | Murder One | Ted Hoffman | Daniel Benzali |

| May 12 | Author of The Scarlet Letter (1850) | Nathaniel Hawthorne |
| May 12 | A Confederacy of Dunces (Pulitzer 1981, posthumous) | John Kennedy Toole |
| May 12 | Garden of Earthly Delights triptych painter | Hieronymus Bosch |
| May 12 | Composer of Carmina Burana (1937) / "O Fortuna" | Carl Orff |
| May 12 | Saturday Evening Post illustrator of Americana | Norman Rockwell |
| May 12 | Chicago poet, 3-time Pulitzer; "Fog comes on little cat feet" | Carl Sandburg |

| May 12 | Hewlett-Packard founded year/place | 1939, Palo Alto garage (Hewlett & Packard) |
| May 12 | Wright Brothers first flight | Dec 17, 1903, Kitty Hawk NC; 12 seconds |
| May 12 | Twinkies invented year/inventor | 1930, James Dewar (Hostess); originally banana cream |
| May 12 | Ben & Jerry's founded year/place | 1978, Burlington VT (gas station) |
| May 12 | Krispy Kreme founded year/place | 1937, Winston-Salem NC (Vernon Rudolph) |
| May 12 | Zippo lighter inventor/year/city | George Blaisdell, 1932, Bradford PA |

| May 12 | Animals | Bee hummingbird (Cuba) — world's smallest bird, ~2.25 in, lighter than a penny |
| May 12 | Biology | Caterpillars dissolve into cellular soup inside chrysalis; only "imaginal" cells survive |
| May 12 | Botany | Brazil nuts only from wild Amazon — depend on specific orchid bee for pollination |
| May 12 | Language | "Rhythms" — longest English word with no vowels (Y as consonant) |
| May 12 | Astronomy | Saturn has 274 confirmed moons (2025 IAU count) — more than rest of solar system combined |
| May 12 | Pop culture | Walt Disney was afraid of mice (created Mickey to face the fear) |
| May 12 | Time | A "moment" was a medieval unit = 90 seconds (1/40 of solar hour) |
| May 12 | History | Einstein offered presidency of Israel in 1952; declined |
| May 12 | Religion | Shortest KJV Bible verse: "Jesus wept" (John 11:35) |
| May 12 | Americana | Liberty Bell hasn't been rung since 1846 (Washington birthday crack) |
| May 12 | Animals | Group of jellyfish = "smack"; group of rhinos = "crash" |
| May 12 | Olympics | 1912–1948 Olympics awarded medals for art (painting, sculpture, architecture, lit, music) |
| May 12 | Sports | Reds 22-19, .537, NL Central 5th (5 GB Cubs); took 2 of 3 from Astros; vs Nationals 6:40 PM ET tonight |
| May 12 | Sports | NBA R2 Conf Semis: Knicks SWEEP 76ers; Thunder 3-0 Lakers; Cavs/Pistons 2-2 (Cavs 23-0 Q3 run); Wolves/Spurs 2-2 (Wemby ejected G4) |
| May 12 | Sports | NHL R2: Hurricanes SWEEP Flyers; Avs 9-6 Wild G2 (15 combined goals); other series tied/early |
| May 12 | Sports | MLB: Cubs win 6 straight (27-14, NL Central runaway); Braves 6 straight; Misiorowski (MIL) 11 K + 103.6 mph fastball MLB debut vs NYY |
| May 12 | Sports | NFL: 2026 schedule release Thu May 14; 9 international games; Cowboys-Giants SNF Wk1, Eagles-Cowboys Thanksgiving, Ravens-Cowboys Rio Sept 27, Rams-49ers Melbourne Sept 11 |
| May 12 | Box Office | Devil Wears Prada 2 holds #1 (~$43M, 2nd wknd) over Mortal Kombat II ($40M dom / $63M global open) |
| May 12 | News | Iran ceasefire on "massive life support" (Trump); Hungary's Magyar ousts Orbán after 16y; UK PM Starmer leadership challenge; Moderna +7.5% on hantavirus vaccine |

| May 12 | Vogue | Madonna | 1990 |
| May 12 | Black or White | Michael Jackson | 1991 |
| May 12 | Mr. Jones | Counting Crows | 1993 |
| May 12 | Killing Me Softly | Fugees | 1996 |
| May 12 | Drops of Jupiter | Train | 2001 |
| May 12 | Empire State of Mind | Jay-Z feat. Alicia Keys | 2009 |

| May 12 | May 12 (Florence Nightingale born 1820; Rolling Stones finish "Satisfaction" 1965; Sichuan earthquake 2008 ~87K dead) | — |
| May 12 | National Days: National Limerick Day (Edward Lear), International Nurses Day, National Nutty Fudge Day, National Odometer Day, Fibromyalgia Awareness Day | — |


| May 13 | Capital of Connecticut | Hartford |
| May 13 | Capital of Vietnam | Hanoi |
| May 13 | Capital of Wyoming | Cheyenne |
| May 13 | Capital of Greece | Athens |

| May 13 | Magnum, P.I. | Thomas Magnum | Tom Selleck |
| May 13 | Cagney & Lacey | Det. Christine Cagney | Sharon Gless |
| May 13 | The X-Files | Fox Mulder | David Duchovny |
| May 13 | Three's Company | Jack Tripper | John Ritter |
| May 13 | Bewitched | Samantha Stephens | Elizabeth Montgomery |
| May 13 | The Mary Tyler Moore Show | Mary Richards | Mary Tyler Moore |

| May 13 | Painter of Guernica (1937) | Pablo Picasso |
| May 13 | Author of I Know Why the Caged Bird Sings (1969) | Maya Angelou |
| May 13 | Composer of 5th Symphony "da-da-da-DUM" | Ludwig van Beethoven |
| May 13 | "Call me Ishmael" opens which 1851 novel | Moby-Dick by Herman Melville |
| May 13 | Mexican self-portraitist; Blue House Coyoacán | Frida Kahlo |
| May 13 | French novelist of In Search of Lost Time / madeleine | Marcel Proust |

| May 13 | Coca-Cola founded year/founder/city | 1886, Atlanta, John Pemberton (pharmacist) |
| May 13 | McDonald's brothers first drive-in year/city | 1940, San Bernardino CA (Richard & Maurice McDonald) |
| May 13 | Levi Strauss & Co. founded year + rivet patent | 1853 SF; rivet patent May 20, 1873 (with Jacob Davis) |
| May 13 | Velcro inventor / inspiration | George de Mestral, 1955; burrs on dog's fur |
| May 13 | Post-it Note company/year/inventors | 3M, 1980 (Spencer Silver adhesive 1968; Art Fry hymnal bookmark 1974) |
| May 13 | Band-Aid inventor/year | Earle Dickson, 1920 (Johnson & Johnson; for accident-prone wife Josephine) |

| May 13 | Animals | Octopuses have three hearts and blue copper-based blood (hemocyanin) |
| May 13 | Animals | Wombat poop is cube-shaped — unique in nature |
| May 13 | Food | Bananas are botanical berries; strawberries are not |
| May 13 | Food | Honey never spoils — edible 3,000-yr-old honey found in Egyptian tombs |
| May 13 | Geography | Shortest commercial flight: Westray–Papa Westray, Scotland (~90 sec) |
| May 13 | Statue of Liberty | Nose is 4'6"; sandal size 879 |
| May 13 | Language | The dot over "i" and "j" is called a "tittle" |
| May 13 | Science | Sharks predate trees (~400M yrs vs ~350M); also predate Saturn's rings |
| May 13 | Time | A "jiffy" is a real unit ≈ 1/100 of a second (or ~1 cm light in vacuum) |
| May 13 | Geography | Great Wall of China NOT visible from space with naked eye (confirmed by Yang Liwei 2003) |
| May 13 | Customs | Sweden's "Lördagsgodis" — Saturday candy day, from 1950s dental health campaign |
| May 13 | Language | English word "set" has the most OED definitions (430+) |
| May 13 | Sports | Reds 22-20, .524, NL Central 5th (5 GB Cubs); lost 10-4 to Nationals Tue, L1 streak, L10 2-8 |
| May 13 | Sports | NBA R2: Thunder SWEEP Lakers (8-0 playoffs); Cavs even Pistons 2-2 (Mitchell 43); Knicks idle in ECF; Wolves/Spurs 2-2 |
| May 13 | Sports | NHL R2: Hurricanes 8-0 playoffs (await ECF); Avs 3-1 Wild (5-2 G4); Sabres 3-2 Habs G4 (Benson PPG) tied 2-2 |
| May 13 | Sports | MLB: Cubs 27-15 (lost 3); Braves 29-13 best in baseball; Rockies 16-26 |
| May 13 | Sports | MLS Matchday 12: Houston 4-1 LAFC (McGlynn 2 G); NYCFC 3-0 Crew (Wolf hat trick); San Jose 1-1 Vancouver |
| May 13 | NFL | 9 international games (Madrid, São Paulo, London, Berlin, Dublin, Melbourne, Rio); Broncos@Chiefs MNF Wk1; Saints-Steelers Paris |
| May 13 | Box Office | Devil Wears Prada 2 #1 2nd wknd $41.6M (verified Wikipedia/Box Office Mojo); Streep $77M opener career best |
| May 13 | News | Trump in Beijing for Xi summit; Iran ceasefire on "life support"; SCOTUS clears AL voting-map elimination; Cambridge near-Harvard shooting |

| May 13 | Gangsta's Paradise | Coolio feat. L.V. | 1995 |
| May 13 | Tubthumping | Chumbawamba | 1997 |
| May 13 | Genie in a Bottle | Christina Aguilera | 1999 |
| May 13 | Livin' la Vida Loca | Ricky Martin | 1999 |
| May 13 | Since U Been Gone | Kelly Clarkson | 2004 |
| May 13 | Hips Don't Lie | Shakira feat. Wyclef Jean | 2006 |

| May 13 | May 13 (Jamestown founded 1607; Churchill "blood, toil, tears and sweat" 1940; Pope John Paul II shot 1981) | — |
| May 13 | National Days: National Apple Pie Day, National Frog Jumping Day, International Hummus Day, World Cocktail Day, Top Gun Day, National Receptionists Day | — |

| May 14 | Capital of New Jersey | Trenton |
| May 14 | Capital of Saudi Arabia | Riyadh |
| May 14 | Capital of Utah | Salt Lake City |
| May 14 | Capital of Chile | Santiago |

| May 14 | Maverick | Bret Maverick | James Garner |
| May 14 | WKRP in Cincinnati | Dr. Johnny Fever | Howard Hesseman |
| May 14 | The Bob Newhart Show | Dr. Robert "Bob" Hartley | Bob Newhart |
| May 14 | Police Woman | Sgt. Pepper Anderson | Angie Dickinson |
| May 14 | Coach | Hayden Fox | Craig T. Nelson |
| May 14 | Boy Meets World | Cory Matthews | Ben Savage |

| May 14 | Author of Charlotte's Web (1952) | E.B. White |
| May 14 | Composer of The Planets suite (1916) | Gustav Holst |
| May 14 | French Impressionist of ballet dancers / racehorses | Edgar Degas |
| May 14 | Author of The Outsiders (1967), written at 16 | S.E. Hinton |
| May 14 | Beat poet who wrote "Howl" (1956) | Allen Ginsberg |
| May 14 | Pulitzer-winning author of The Road (2007) | Cormac McCarthy |

| May 14 | Dr Pepper invented year/inventor | 1885, Charles Alderton, Waco TX |
| May 14 | Hoover vacuum patent (1908) | James Murray Spangler (sold to W.H. Hoover) |
| May 14 | Bubble gum (Dubble Bubble) inventor/year | Walter Diemer, Fleer Chewing Gum, 1928 |
| May 14 | Cheerios original name/year | "CheeriOats," 1941 (General Mills); renamed 1945 |
| May 14 | Procter & Gamble founded year/city | 1837, Cincinnati OH (Procter + Gamble brothers-in-law) |
| May 14 | Apple Macintosh release date | January 24, 1984 (Ridley Scott Super Bowl XVIII "1984" ad) |

| May 14 | Animals | Hippos kill more humans annually in Africa than lions/sharks/crocodiles combined |
| May 14 | Animals | Squirrels plant thousands of trees by forgetting buried acorns |
| May 14 | Anatomy | Hyoid bone in throat — only bone not connected to another bone |
| May 14 | Science | Earth is oblate spheroid; ~13 mi wider at equator |
| May 14 | Pop culture | Mickey Mouse's full name is Michael Theodore Mouse |
| May 14 | Astronomy | 55 Cancri e — "diamond planet" ~40 ly away, carbon-crystal core |
| May 14 | Geography | Lake Superior holds enough water to cover N+S America 1 ft deep |
| May 14 | Animals | Honeybees can recognize individual human faces (configural processing) |
| May 14 | Engineering | Empire State Building has its own ZIP code: 10118 |
| May 14 | Probability | Opposite sides of a standard die always sum to 7 |
| May 14 | Food | Most commercial lipsticks contain guanine — derived from fish scales |
| May 14 | History | Sandwich named after 4th Earl of Sandwich (John Montagu), ~1762 |
| May 14 | Sports | Reds 22-21, .512, NL Central 5th (5 GB Cubs 27-16); vs Nationals 12:40 PM ET; L2, L10 2-8 |
| May 14 | Sports | NBA R2: Thunder SWEEP Lakers (8-0 playoffs); Knicks SWEEP 76ers; Cavs/Pistons 2-2; Wolves/Spurs 2-2 |
| May 14 | Sports | NHL R2: Hurricanes SWEEP Flyers (8-0); Avalanche eliminate Wild in 5 (Kulak OT GWG); Sabres/Habs 2-2 |
| May 14 | NFL | 2026 schedule release TODAY; Cowboys @ Giants SNF Wk1; Ravens-Cowboys Rio Sept 27; Eagles-Cowboys Thanksgiving |
| May 14 | MLS | Messi 3 G in Inter Miami 5-3 @ FC Cincinnati (89th-min ruled OG; doubles salary to $28M/yr) |
| May 14 | Box Office | Devil Wears Prada 2 $144.8M dom / $433.2M global; Mortal Kombat II opens #2 $40M; Sheep Detectives 97% RT |

| May 14 | Torn | Natalie Imbruglia | 1997 |
| May 14 | Bitter Sweet Symphony | The Verve | 1997 |
| May 14 | Iris | Goo Goo Dolls | 1998 |
| May 14 | Mambo No. 5 (A Little Bit of...) | Lou Bega | 1999 |
| May 14 | How You Remind Me | Nickelback | 2001 |
| May 14 | Clocks | Coldplay | 2002 |

| May 14 | May 14 (Jamestown 1607; Lewis & Clark depart 1804; Israel proclaimed 1948; Skylab launched 1973) | — |
| May 14 | National Days: Stars and Stripes Forever Day, Dance Like a Chicken Day, International Dylan Thomas Day, National Buttermilk Biscuit Day, National Underground America Day | — |


_Last updated: May 14, 2026 (v8 — Today pill + dated pills, Today always first linking to index.html)_
