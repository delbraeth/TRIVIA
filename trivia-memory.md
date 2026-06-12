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
| May 20 | Capital of South Carolina | Columbia |
| May 20 | Capital of Mexico | Mexico City |
| May 20 | Capital of Estonia | Tallinn |
| May 20 | Capital of Botswana | Gaborone |



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
| May 20 | The Untouchables | Eliot Ness | Robert Stack |
| May 20 | My Three Sons | Steve Douglas | Fred MacMurray |
| May 20 | McMillan & Wife | Stewart McMillan | Rock Hudson |
| May 20 | The Prisoner | Number Six | Patrick McGoohan |
| May 20 | F Troop | Capt. Wilton Parmenter | Ken Berry |
| May 20 | Xena: Warrior Princess | Xena | Lucy Lawless |


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
| May 20 | A Farewell to Arms | Ernest Hemingway |
| May 20 | The Great Wave off Kanagawa | Katsushika Hokusai |
| May 20 | The Barber of Seville (opera) | Gioachino Rossini |
| May 20 | A Wrinkle in Time | Madeleine L'Engle |
| May 20 | The Gulf Stream / Snap the Whip painter | Winslow Homer |
| May 20 | The Aeneid | Virgil |


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
| May 20 | Botany | Bananas are berries; strawberries are not |
| May 20 | Animals | Mosquitoes kill more humans/year than any animal |
| May 20 | Aviation | 'Black box' flight recorder is painted bright orange |
| May 20 | Animal Group | A group of foxes is a 'skulk' (or 'leash') |
| May 20 | Astronomy | Sun = 99.86% of solar system's mass |
| May 20 | History | Pope John Paul I served only 33 days in 1978 |
| May 20 | History | Bayeux Tapestry is embroidery, not tapestry; ~230 ft long |
| May 20 | UK History | Tower of London by decree must keep 6 ravens |
| May 20 | Business | Kongō Gumi (578 AD Japan) — world's oldest company |
| May 20 | Language | Papua New Guinea has 800+ living languages |
| May 20 | Invention | Eyeglasses invented in Italy ~1290 |
| May 20 | Biology | Komodo dragon bite is venomous (confirmed 2009) |


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
| May 20 | May 20 (Homestead Act 1862; Lindbergh 1927; Earhart 1932) |


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
| May 20 | World Bee Day · World Metrology Day · National Rescue Dog Day · Clinical Trials Day · National Be a Millionaire Day |


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
| May 20 | Yahoo! founders/year | 1994, Jerry Yang & David Filo (Stanford) |
| May 20 | Sony Walkman release year | 1979 (TPS-L2) |
| May 20 | Computer mouse inventor | Douglas Engelbart (1964, patented 1970) |
| May 20 | Pac-Man release | Namco, 1980, designed by Toru Iwatani |
| May 20 | White-Out / Liquid Paper inventor | Bette Nesmith Graham, 1956 (Michael Nesmith's mother) |
| May 20 | Frozen food industry pioneer | Clarence Birdseye, 1920s |


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




| May 14b | Capital of Alabama | Montgomery |
| May 14b | Capital of Denmark | Copenhagen |
| May 14b | Capital of California | Sacramento |
| May 14b | Capital of Bangladesh | Dhaka |

| May 14b | Maude | Maude Findlay | Bea Arthur |
| May 14b | Highway to Heaven | Jonathan Smith | Michael Landon |
| May 14b | Star Trek: Voyager | Capt. Kathryn Janeway | Kate Mulgrew |
| May 14b | Mad About You | Paul Buchman | Paul Reiser |
| May 14b | Empty Nest | Dr. Harry Weston | Richard Mulligan |
| May 14b | Father Knows Best | Jim Anderson | Robert Young |

| May 14b | Author of Fahrenheit 451 (1953) | Ray Bradbury |
| May 14b | Irish author of Dracula (1897) | Bram Stoker |
| May 14b | Norwegian playwright of A Doll's House (1879) | Henrik Ibsen |
| May 14b | Russian composer of Pictures at an Exhibition (1874) | Modest Mussorgsky |
| May 14b | French Neoclassical painter of The Death of Marat (1793) | Jacques-Louis David |
| May 14b | Author of Jane Eyre (1847) | Charlotte Brontë |

| May 14b | KFC founder/year | Harland "Colonel" Sanders, 1930 (Corbin KY service station) |
| May 14b | Tabasco sauce inventor/year/place | Edmund McIlhenny, 1868, Avery Island LA |
| May 14b | Ford Mustang debut | April 17, 1964, New York World's Fair |
| May 14b | Tic Tac introduced | 1969 by Ferrero (Italy) |
| May 14b | Goodyear Tire founded year/founder | 1898, Frank Seiberling; named after Charles Goodyear |
| May 14b | Etch A Sketch inventor/year | André Cassagnes, 1959 (Ohio Art Co. 1960) |

| May 14b | Etymology | "Pencil lead" is graphite; 1564 Borrowdale England find |
| May 14b | Etymology | "OK" from 1839 Boston Morning Post "oll korrect" joke |
| May 14b | Geography | Antarctica = only continent with no native reptiles/snakes/amphibians |
| May 14b | Botany | Banana plants are herbs, not trees (pseudostem of leaves) |
| May 14b | Animals | Goldfish 5-second memory is a myth — they remember for months |
| May 14b | Food | Hot dogs originally sold as "dachshund sausages" in 1860s US |
| May 14b | Pop culture | Hollywood Sign read "HOLLYWOODLAND" 1923–1949 |
| May 14b | Geography | Atlantic Ocean widens ~1 inch (2.5 cm) per year at Mid-Atlantic Ridge |
| May 14b | Symbols | Mozambique only national flag depicting modern firearm (AK-47) |
| May 14b | History/Food | Lobster fed to colonial-era prisoners; servings capped twice/wk |
| May 14b | Sports | Reds 22-21 .512, 5th NL Central 5 GB Cubs; L7 of 10 (2-8 L10); vs Nationals 12:40 PM ET |
| May 14b | Sports | NBA R2: Spurs 126-97 Wolves G5 (Wemby 26 returns, SAS 3-2); Cavs 117-113 OT Pistons G5 (Harden 30/8/6, CLE 3-2); Knicks SWEEP 76ers; Thunder SWEEP Lakers |
| May 14b | Sports | NHL R2: Avalanche eliminate Wild in 5 (Kulak OT GWG); Hurricanes 8-0 playoffs; Habs/Sabres G5 tied 2-2; VGK/Ducks G6 |
| May 14b | NFL | 2026 schedule release today; 9 international games (Rio, Madrid, Melbourne, Berlin); Cowboys-Giants SNF Wk1 |
| May 14b | MLS | Messi 3-G in Miami 5-3 @ FC Cincinnati; Vancouver Whitecaps best start |
| May 14b | Box Office | Devil Wears Prada 2 #1 2nd wknd $41.6M; $151.6M dom/$441.4M global (verified Variety/Deadline); biggest Streep opener; surpassed original $326M lifetime in 2 weekends |
| May 14b | Deaths | Lou Graham (88, 1975 US Open champ); Jack Douglas (80, producer Aerosmith/Lennon); Jonathan Tiersten (60, Sleepaway Camp); Hany Shaker (73, Egyptian singer) |
| May 14b | News | NFL schedule release; first NCAA football in Canada (Wake/Syracuse 2027 Toronto); Iran ceasefire; UK Starmer challenge; Trump-Xi summit |

| May 14b | Nothing Compares 2 U | Sinéad O'Connor | 1990 |
| May 14b | End of the Road | Boyz II Men | 1992 |
| May 14b | Macarena (Bayside Boys Remix) | Los del Río | 1996 |
| May 14b | MMMBop | Hanson | 1997 |
| May 14b | Crazy | Gnarls Barkley | 2006 |
| May 14b | I Gotta Feeling | Black Eyed Peas | 2009 |

| May 14b | May 14 alt (Jenner smallpox vaccination 1796; Rotterdam bombing 1940; Mrs Dalloway pub 1925; Battle of Lewes 1264) | — |
| May 14b | National Days: Ascension Day, National Brioche Day, National Chihuahua Appreciation Day, Spinal Cord Injury Awareness Day | — |


| May 14c | Capital of Maine | Augusta |
| May 14c | Capital of New Mexico | Santa Fe |
| May 14c | Capital of Ireland | Dublin |
| May 14c | Capital of Indonesia | Jakarta |

| May 14c | Have Gun – Will Travel | Paladin | Richard Boone |
| May 14c | The Carol Burnett Show | Carol Burnett (host) | Carol Burnett |
| May 14c | Leave It to Beaver | Theodore "Beaver" Cleaver | Jerry Mathers |
| May 14c | Family Affair | Mr. French | Sebastian Cabot |
| May 14c | Law & Order | Det. Lennie Briscoe | Jerry Orbach |
| May 14c | 3rd Rock from the Sun | Dick Solomon | John Lithgow |

| May 14c | Author of Lord of the Flies (1954, Nobel 1983) | William Golding |
| May 14c | Polish-born composer of nocturnes / "Minute Waltz" | Frédéric Chopin |
| May 14c | Norwegian composer of "Peer Gynt" / "In the Hall of the Mountain King" | Edvard Grieg |
| May 14c | Russian-French painter of dreamlike floating figures/fiddlers | Marc Chagall |
| May 14c | Russian author of Doctor Zhivago (1957, declined Nobel 1958) | Boris Pasternak |
| May 14c | Italian opera composer of La Bohème, Tosca, Madame Butterfly | Giacomo Puccini |

| May 14c | Burger King founded year/city | 1953/54, Jacksonville FL (Edgerton & McLamore) |
| May 14c | Domino's Pizza founded year/founder/city | 1960, Tom Monaghan, Ypsilanti MI |
| May 14c | Practical sewing machine patent / commercializer | Elias Howe 1846; Isaac Singer 1851 |
| May 14c | IBM founded year / original name | 1911 as CTR (Computing-Tabulating-Recording); renamed 1924 |
| May 14c | Saxophone inventor / year / country | Adolphe Sax, 1846 (Belgium) |
| May 14c | First fully electronic television inventor / year | Philo Farnsworth, 1927 |

| May 14c | Animals | Starfish have no brain and no blood — circulate seawater instead |
| May 14c | Animals | Polar bears classified as marine mammals (only bear so designated) |
| May 14c | Astronomy | Olympus Mons (Mars) ~13.6 mi tall — tallest volcano in solar system |
| May 14c | Astronomy | Jupiter has 95+ confirmed moons — most of any planet |
| May 14c | Geography | Dead Sea ~9.6× saltier than ocean (~34% salinity) |
| May 14c | Geography | Istanbul straddles two continents (Europe & Asia) via Bosporus |
| May 14c | Botany | Bamboo fastest-growing plant — up to 35 in (89 cm)/day |
| May 14c | History | Magna Carta (1215) was sealed, not signed, by King John |
| May 14c | Etymology | "Goodbye" = contraction of "God be with ye" |
| May 14c | Etymology | "Quarantine" from Italian quaranta giorni (40 days), Venice plague |
| May 14c | Pop culture | Mr. Potato Head — first toy advertised on TV (1952); originally real potato |
| May 14c | Sports | Indianapolis 500 winner gets a bottle of milk in Victory Lane since 1936 (Louis Meyer) |
| May 14c | Sports | Reds 23-21 .523, 5th NL Central 4.5 GB Cubs 27-16; BEAT Nationals 15-1; L10 3-7; streak W1 |
| May 14c | Sports | NBA R2: Spurs 3-2 Wolves (G6 tonight 7pm); Cavs 3-2 Pistons (G6 5/15); Knicks SWEEP 76ers; Thunder SWEEP Lakers |
| May 14c | Sports | NHL R2: Hurricanes SWEEP Flyers (8-0); Avalanche eliminate Wild in 5; Habs/Sabres 2-2 G5 tonight; VGK 3-2 Ducks G6 9:30pm |
| May 14c | NFL | 2026 schedule released 8pm ET tonight; 9 intl games (Rio, Madrid, Melbourne, Berlin, London, Paris, Munich, Mexico City, Dublin); Cowboys @ Giants SNF Wk1 Sept 13; Ravens-Cowboys Rio Wk3; Cowboys-Eagles Thanksgiving |
| May 14c | MLS | Messi 2G/1A + forces 89th-min OG — Inter Miami 5-3 @ FC Cincinnati; new $28.3M salary (2× Son Heung-min); 11G/5A season |
| May 14c | Box Office | Devil Wears Prada 2 2nd wknd $43M (44% drop); $144.8M dom/$433M global; Mortal Kombat II #2 $40M open; Michael #3 $36.5M |
| May 14c | Box Office | Weekend May 15-17: Shrek re-release; Driver's Ed; Magic Hour; Forge |
| May 14c | Deaths | Jason Collins (47, 1st openly gay NBA player, glioblastoma, May 12); Michael Pennington (82, British actor, Moff Jerjerrod in ROTJ, May 7); Ted Turner (87, CNN founder, Lewy Body, May 6) |
| May 14c | News | Trump-Xi 2-day summit opens Beijing (Musk/Cook/Fink/Ortberg in delegation); Iran ceasefire stalled, "Martyr Commander" 5-day exercise; UK State Opening (King Charles reads Labour agenda), Starmer leadership challenge |

| May 14c | Vision of Love | Mariah Carey | 1990 |
| May 14c | Jeremy | Pearl Jam | 1992 |
| May 14c | Ironic | Alanis Morissette | 1995 |
| May 14c | Genie in a Bottle | Christina Aguilera | 1999 |
| May 14c | American Idiot | Green Day | 2004 |
| May 14c | Use Somebody | Kings of Leon | 2008 |

| May 14c | May 14 alt (Henry IV France assassinated by Ravaillac 1610; George Lucas born 1944; Warsaw Pact signed 1955) | — |
| May 14c | National Days: Paraguay Independence Day (1811, first SA nation independent of Spain); National Decency Day; Bond With Your Dog Day; World Migratory Bird Day | — |


| May 14d | Capital of Arizona | Phoenix |
| May 14d | Capital of Austria | Vienna |
| May 14d | Capital of Poland | Warsaw |
| May 14d | Capital of North Carolina | Raleigh |

| May 14d | Leave It to Beaver | Beaver Cleaver | Jerry Mathers |
| May 14d | The Man from U.N.C.L.E. | Napoleon Solo | Robert Vaughn |
| May 14d | Dark Shadows | Barnabas Collins | Jonathan Frid |
| May 14d | A Different World | Dwayne Wayne | Kadeem Hardison |
| May 14d | Melrose Place | Amanda Woodward | Heather Locklear |
| May 14d | The Commish | Tony Scali | Michael Chiklis |

| May 14d | Italian opera composer of La Bohème, Tosca, Madama Butterfly | Giacomo Puccini |
| May 14d | Spanish painter of "The Third of May 1808" | Francisco Goya |
| May 14d | Irish poet who wrote "The Second Coming" (1919) | W.B. Yeats |
| May 14d | British modernist author of Mrs Dalloway and To the Lighthouse | Virginia Woolf |
| May 14d | British author of Sons and Lovers and Lady Chatterley's Lover | D.H. Lawrence |
| May 14d | Norwegian Romantic composer of "Peer Gynt Suite" / Piano Concerto A minor | Edvard Grieg |

| May 14d | Silly Putty inventor/year/purpose | James Wright, 1943, failed synthetic rubber |
| May 14d | Hula Hoop (Wham-O 1958) — units sold in 4 months | 25 million |
| May 14d | Barbie doll debut date/creator | March 9, 1959; Ruth Handler (Mattel) |
| May 14d | Popsicle inventor/year/age | Frank Epperson, 1905, age 11 |
| May 14d | Cracker Jack — first appeared at which event (1893) | World's Columbian Exposition, Chicago |
| May 14d | Jell-O sold for what price (1899) | $450 (to Genesee Pure Food Company) |

| May 14d | Animals | Blue whale's tongue alone weighs as much as an elephant (~6,000 lbs) |
| May 14d | Language | "Emoji" from Japanese: 絵 (e=picture) + 文字 (moji=character) — not from "emotion" |
| May 14d | History | "Deadline" originated in Civil War prison camps — crossing line = shot |
| May 14d | Etymology | "Berserk" from Old Norse berserkr — Viking warriors in battle frenzy |
| May 14d | Animals | Group of ravens = "unkindness" or "conspiracy" |
| May 14d | Geography | Russia borders 14 countries — more than any other nation |
| May 14d | Animals | Narwhal's "horn" is a tooth (single enlarged canine) up to 10 ft |
| May 14d | Astronomy | Moon footprints last ~100 million years (no wind/weather) |
| May 14d | Food | Cavendish banana replaced Gros Michel (wiped out by Panama disease, 1950s) |
| May 14d | History | Playing cards invented Tang Dynasty China (~9th c. AD); Europe adopted 14th c. |
| May 14d | Science | Birthday paradox: 23 people = 50%+ chance two share same birthday |
| May 14d | Animals | Horses sleep standing via "stay apparatus" — locking knee/joint mechanism |
| May 14d | Sports | Reds 23-21 .523, 5th NL Central 4.5 GB Cubs 27-16; BEAT Nationals 15-1; L10 3-7; streak W1 |
| May 14d | Sports | NBA R2: Spurs 3-2 Wolves (G6); Cavs 3-2 Pistons (G6 5/15); Knicks SWEEP 76ers; Thunder SWEEP Lakers |
| May 14d | Sports | NHL R2: Hurricanes SWEEP Flyers; Avalanche elim Wild; Sabres/Habs 2-2; VGK 3-2 Ducks |
| May 14d | Sports | Messi hat trick — Inter Miami 5-3 @ FC Cincinnati; salary doubled to $28M |
| May 14d | NFL | 2026 schedule released today; Cowboys @ Giants SNF Wk1; 9 international games |
| May 14d | Box Office | Devil Wears Prada 2 2nd wknd $41.6M; $151.6M dom/$441.4M global; MK2 #2 $40M; Sheep Detectives #3 $15.9M 97%RT |
| May 14d | Deaths | Ted Turner (87, CNN founder); Michael Pennington (82, Star Wars ROTJ); Desmond Morris (98, The Naked Ape); Dave Mason (79, Traffic) |
| May 14d | News | Trump-Xi summit Beijing; Iran war Senate 50-49; Israeli strikes Lebanon; NFL schedule; Hungary/Orbán ousted; Moderna hantavirus +7.5% |

| May 14d | Everlong | Foo Fighters | 1997 |
| May 14d | Say My Name | Destiny's Child | 1999 |
| May 14d | Wannabe | Spice Girls | 1996 |
| May 14d | Black | Pearl Jam | 1991 |
| May 14d | All I Wanna Do | Sheryl Crow | 1993 |

| May 14d | May 14: WAAC established 1942; Warsaw Pact signed 1955 (also May 14c); Frank Sinatra dies 1998 | — |
| May 14d | National Days: World Migratory Bird Day; National Decency Day; National Temperature Control Day; National Chicken Dance Day | — |



| May 18 | Capital of Wyoming | Cheyenne |
| May 18 | Capital of Thailand | Bangkok |
| May 18 | Capital of Maine | Augusta |
| May 18 | Capital of Ireland | Dublin |

| May 18 | The Andy Griffith Show | Sheriff Andy Taylor | Andy Griffith |
| May 18 | M*A*S*H | Capt. "Hawkeye" Pierce | Alan Alda |
| May 18 | Magnum, P.I. | Thomas Magnum | Tom Selleck |
| May 18 | Murder, She Wrote | Jessica Fletcher | Angela Lansbury |
| May 18 | Bewitched | Samantha Stephens | Elizabeth Montgomery |
| May 18 | Columbo | Lt. Columbo | Peter Falk |

| May 18 | "It was the best of times" opener — A Tale of Two Cities (1859) | Charles Dickens |
| May 18 | Author of Beloved (1987 Pulitzer; 1993 Nobel Lit) | Toni Morrison |
| May 18 | Composer of Swan Lake / Nutcracker / 1812 Overture | Pyotr Ilyich Tchaikovsky |
| May 18 | Painter of Guernica (1937) | Pablo Picasso |
| May 18 | Norwegian playwright of A Doll's House (1879) | Henrik Ibsen |
| May 18 | Designer of Vietnam Veterans Memorial (1981, Yale undergrad) | Maya Lin |

| May 18 | Hewlett-Packard founding year/city/founders | 1939, Palo Alto garage (Hewlett & Packard); birthplace of Silicon Valley |
| May 18 | Pizza Hut founded year/city/founders | 1958, Wichita KS, Dan & Frank Carney ($600 from mom) |
| May 18 | Tupperware inventor and year | Earl Tupper, 1946 (Tupperware Parties via Brownie Wise) |
| May 18 | Tabasco sauce inventor and year | Edmund McIlhenny, 1868, Avery Island LA |
| May 18 | Spotify founders/year/country | Daniel Ek & Martin Lorentzon, 2006, Stockholm Sweden |
| May 18 | Q-tips original brand name (1923) | "Baby Gays" — Leo Gerstenzang; renamed Q-tips 1926 |

| May 18 | Biology | Octopuses have 3 hearts and blue copper-based blood (hemocyanin); main heart stops when swimming |
| May 18 | Evolution | Sharks predate trees — sharks ~450M yrs vs first trees ~385M yrs |
| May 18 | Astronomy | Lightning bolt ~30,000K — ~5× hotter than the Sun's surface (~5,778K) |
| May 18 | Food | Honey never spoils — 3,000-yr-old Egyptian tomb honey still edible |
| May 18 | Botany | Bananas are berries; strawberries are not (aggregate accessory fruits) |
| May 18 | History | Cleopatra lived closer to first Pizza Hut (1958) than to Great Pyramid (~2560 BC) |
| May 18 | Language | Hawaiian alphabet has 13 letters incl. the ʻokina |
| May 18 | Animals | Wombat scat is cube-shaped — only known cube-pooping animal |
| May 18 | Astronomy | Pluto hasn't completed 1 orbit since 1930 discovery (248-yr year) |
| May 18 | Geography | Antarctica is the largest desert (~5.5M sq mi); <2 in/yr precipitation interior |
| May 18 | Anatomy | Babies born w/ ~270 bones; adults 206 (skull plates fuse) |
| May 18 | Etymology | Pencil "lead" is graphite — misidentified in 1500s Cumbria |
| May 18 | Sports | Reds 24-23 .511 5th NL Central 5 GB Cubs (29-18); L10 4-6, streak L2; @ Phillies 6:40 PM ET |
| May 18 | Sports | NBA Conf Finals tip off: Thunder-Spurs (W) tonight 8:30 PM NBC; Knicks-Cavs (E) Tue 5/19 8 PM ESPN |
| May 18 | Sports | NHL R2 G7 Canadiens-Sabres tonight 7:30 PM ESPN; W Final Avalanche-Knights starts Wed 5/20 |
| May 18 | Sports | MLS: Messi G+A, Inter Miami 2-0 Portland first Nu Stadium win; 13G/6A, 18 GC |
| May 18 | NFL | OTAs begin league-wide; Rodgers signs 1-yr/$25M Steelers, QB1 reps |
| May 18 | Box Office | Michael ~$26M 4th wknd; $580M dom/$703M global; Obsession #2 $16M open |
| May 18 | Deaths | Donald Gibb (71, Ogre in Revenge of the Nerds, May 12); Clarence Carter (90, blues/soul "Patches" "Strokin'", May 14); Claudine Longet (84, French singer/actress Love Is Blue, May 15) |
| May 18 | News | NBA Conf Finals begin; Rodgers to Steelers; Mt St Helens 46th anniversary; Ukraine drone strike near Moscow kills 4; UAE nuclear plant drone fire; Mandalorian and Grogu opens 5/22; Amnesty: 2025 state executions 44-yr high |

| May 18 | May 18 (Mt St Helens erupts 1980 — 57 killed; Napoleon proclaimed Emperor 1804; Bath School disaster 1927 — 44 killed; US Selective Service Act 1917) | — |
| May 18 | National Days: International Museum Day; World AIDS Vaccine Day; I Love Reese's Day; Visit Your Relatives Day; National No Dirty Dishes Day; Victoria Day (Canada); Norway Constitution Day | — |

| May 18 | Mr. Jones | Counting Crows | 1993 |
| May 18 | Black Hole Sun | Soundgarden | 1994 |
| May 18 | 1979 | The Smashing Pumpkins | 1995 |
| May 18 | Don't Speak | No Doubt | 1996 |
| May 18 | Bitter Sweet Symphony | The Verve | 1997 |
| May 18 | Hot in Herre | Nelly | 2002 |


| May 20b | Capital of Iran | Tehran |
| May 20b | Capital of Singapore | Singapore (city-state) |
| May 20b | Capital of South Dakota | Pierre |
| May 20b | Capital of Lithuania | Vilnius |

| May 20b | The Partridge Family | Shirley Partridge | Shirley Jones |
| May 20b | Knots Landing | Karen MacKenzie (née Fairgate) | Michele Lee |
| May 20b | The Equalizer (1985) | Robert McCall | Edward Woodward |
| May 20b | NewsRadio | Dave Nelson | Dave Foley |
| May 20b | Spin City | Mike Flaherty | Michael J. Fox |
| May 20b | Will & Grace | Will Truman | Eric McCormack |

| May 20b | A Clockwork Orange (1962) | Anthony Burgess |
| May 20b | The Hay Wain (1821) | John Constable |
| May 20b | Tristan und Isolde (1865 opera) | Richard Wagner |
| May 20b | Middlesex (2003 Pulitzer) | Jeffrey Eugenides |
| May 20b | The Awakening (1899) | Kate Chopin |
| May 20b | Sculptor of Mount Rushmore | Gutzon Borglum |

| May 20b | Hot Wheels — year/company/creator | 1968, Mattel (Elliot Handler) |
| May 20b | Scrabble — inventor/original name | Alfred Mosher Butts, 1933 — "Lexiko"; rebranded by James Brunot 1948 |
| May 20b | Trivial Pursuit — year/city | 1979, Montreal (Chris Haney & Scott Abbott) |
| May 20b | Sony PlayStation — Japan release | December 3, 1994 |
| May 20b | Honda Motor Co — year/founder | 1948, Soichiro Honda |
| May 20b | iPod — release date/project lead | October 23, 2001 (Tony Fadell) |

| May 20b | Animals | Greenland sharks live up to ~400 years (oldest known vertebrate) |
| May 20b | Geography | Atacama Desert — parts gone 500+ years without rain |
| May 20b | History | Coconut water used as IV plasma substitute in WWII Pacific |
| May 20b | Biology | Wood frogs freeze solid in winter, thaw alive in spring |
| May 20b | Geography | Great Pyramid of Cholula (Mexico) — world's largest pyramid by volume |
| May 20b | Science | Spider silk ~5× stronger than steel by weight |
| May 20b | Animals | Sea otters — ~1M hairs per sq inch, densest fur in animal kingdom |
| May 20b | Geography | Bay of Fundy (NS/ME) — world's highest tides (~50 ft) |
| May 20b | Animals | Cats sweat only through their paw pads |
| May 20b | Astronomy | Voyager 1 — interstellar space since 2012, farthest human-made object |
| May 20b | Sports | Reds 26-24, .520, 4th NL Central 4 GB Brewers; beat Phillies 9-4 today (W2, L10 5-5); no game Thu, vs STL Fri 5/22 |
| May 20b | Sports | NBA Conf Finals: Knicks 22-pt OT comeback G1 vs Cavs (Brunson 38); Spurs 122-115 2OT G1 vs Thunder (Wemby 41/24); both G1s went to OT |
| May 20b | Sports | NHL Conf Finals begin: VGK @ COL Wed 5/20 8 ET; MTL @ CAR Thu 5/21 8 ET |
| May 20b | Sports | NFL: Rodgers reports Steelers OTAs day one (1-yr/$25M) |
| May 20b | MLS | Inter Miami 2-0 Portland (first Nu Stadium home win); La Familia silent protest 85 min; Messi 4G/4A May |
| May 20b | Box Office | Michael $26.1M #1 (4th wknd, $580M dom/$703M global); Devil Wears Prada 2 $17.8M; Obsession opens #3 $17.1M |
| May 20b | Deaths | Brad Arnold (48, 3 Doors Down lead singer, kidney cancer); Claudine Longet (84); Clarence Carter (90) |

| May 20b | May 20 (First Council of Nicaea 325; Cuba indep from US occupation 1902; first Auschwitz prisoners 1940) | — |
| May 20b | National Days: National Streaming Day; National Pick Strawberries Day; National Juice Slush Day; EMS for Children Day; Cannes Film Festival | — |

| May 20b | U Can't Touch This | MC Hammer | 1990 |
| May 20b | Friday I'm in Love | The Cure | 1992 |
| May 20b | Karma Police | Radiohead | 1997 |
| May 20b | Bring Me to Life | Evanescence | 2003 |
| May 20b | Misery Business | Paramore | 2007 |
| May 20b | Hey, Soul Sister | Train | 2009 |


| May 21 | Capital of New Hampshire | Concord |
| May 21 | Capital of Malaysia | Kuala Lumpur |
| May 21 | Capital of Rhode Island | Providence |
| May 21 | Capital of Azerbaijan | Baku |

| May 21 | I Spy | Alexander Scott | Bill Cosby |
| May 21 | Hercules: The Legendary Journeys | Hercules | Kevin Sorbo |
| May 21 | The Drew Carey Show | Drew Carey | Drew Carey |
| May 21 | Hunter | Sgt. Rick Hunter | Fred Dryer |
| May 21 | Diagnosis: Murder | Dr. Mark Sloan | Dick Van Dyke |
| May 21 | Simon & Simon | A.J. & Rick Simon | Jameson Parker & Gerald McRaney |

| May 21 | F. Scott Fitzgerald's 1920 debut novel | This Side of Paradise |
| May 21 | Author of The Sound and the Fury (1929); Nobel 1949 | William Faulkner |
| May 21 | English composer of "Pomp and Circumstance Marches" | Edward Elgar |
| May 21 | Author of A Room with a View (1908) and Howards End | E.M. Forster |
| May 21 | Composer of Adagio for Strings (1936) | Samuel Barber |
| May 21 | Mexican muralist; Detroit Industry; husband of Frida Kahlo | Diego Rivera |

| May 21 | Volkswagen Beetle first produced year/country | 1938, Germany (Porsche design; KdF-Wagen program) |
| May 21 | Cotton gin inventor and year | Eli Whitney, 1793 (patented 1794) |
| May 21 | Costco founded year/founders/city | 1983, Seattle WA (Jeff Brotman & James Sinegal) |
| May 21 | First handheld cellular phone call — who/when | Martin Cooper (Motorola), April 3, 1973 |
| May 21 | Dynamite inventor and year | Alfred Nobel, 1867 |
| May 21 | Marvel Comics founded year/original name | 1939 as "Timely Publications" (Martin Goodman); renamed 1961 |

| May 21 | Animals | Bumblebees recognize human faces; teach each other novel tasks (ball-rolling) |
| May 21 | Science | Helium discovered in Sun's spectrum 1868 — 27 yrs before found on Earth |
| May 21 | Astronomy | Saturn's north pole hexagonal storm ~20,000 mi wide (wider than 2 Earths) |
| May 21 | History | Coca-Cola contained ~9 mg cocaine/glass until 1903 (switched to "spent" coca leaves) |
| May 21 | Animals | Group of butterflies = "kaleidoscope" (or "flutter") |
| May 21 | Botany | Strawberries ~200 seeds outside; aren't true berries (bananas/watermelons are) |
| May 21 | Geography | Lake Titicaca (Peru/Bolivia) = highest navigable lake (~12,500 ft) |
| May 21 | Language | "Pangram" = sentence using every letter; quick brown fox is 33 letters |
| May 21 | Engineering | Hoover Dam concrete still curing today (will harden 100+ more years) |
| May 21 | History | Vikings reached North America (L'Anse aux Meadows) ~1000 AD — 500 yrs before Columbus |
| May 21 | Astronomy | Mount Everest grows ~4 mm/year (Indian Plate subducting under Eurasian) |
| May 21 | Anatomy | Index finger has more touch receptors than middle; lips/tongue most sensitive |
| May 21 | Sports | Reds 26-24 .520 T-4th NL Central 4.5 GB Brewers (29-18); no game today; vs STL Fri 5/22 6:40 PM ET |
| May 21 | Sports | NBA Conf Finals: Knicks 115-104 OT G1 vs Cavs (Brunson 38, 22-pt comeback); G2 tonight; Spurs/Thunder 1-1 (Wemby 41/24 G1 2OT) |
| May 21 | Sports | NHL Conf Finals: Hurricanes-Canadiens G1 tonight 8 ET; Vegas 4-2 Avalanche G1 |
| May 21 | Sports | NFL OTAs underway; Rodgers reports Steelers day one (1-yr/$25M) |
| May 21 | MLS | Messi MLS Team of Matchday; 4G/4A in May; Miami 2-0 Portland first home win at Nu Stadium |
| May 21 | Box Office | Michael $26.1M #1 4th wknd ($580M dom/$703M global); Prada 2 $17.8M; Obsession $17.1M open; Mandalorian & Grogu opens 5/22 (~$82M projected) |
| May 21 | Deaths | Tom Kane (64, voice of Yoda in Clone Wars, Powerpuff Girls Utonium, Archer narrator, May 18); Brad Arnold (48, 3 Doors Down, May 18); Claudine Longet (84, May 15) |

| May 21 | Crash Into Me | Dave Matthews Band | 1996 |
| May 21 | Stan (feat. Dido) | Eminem | 2000 |
| May 21 | Ms. Jackson | OutKast | 2000 |
| May 21 | Maps | Yeah Yeah Yeahs | 2003 |
| May 21 | Float On | Modest Mouse | 2004 |
| May 21 | Hey There Delilah | Plain White T's | 2006 |

| May 21 | May 21 (FIFA founded Paris 1904; Leopold & Loeb murder Bobby Franks 1924; Rajiv Gandhi assassinated 1991) | — |
| May 21 | National Days: International Tea Day (UN); World Day for Cultural Diversity (UN); Global Accessibility Awareness Day; Red Cross Founder's Day; Talk Like Yoda Day; National Waitstaff Day | — |


| May 22 | Capital of Philippines | Manila |
| May 22 | Capital of Jordan | Amman |
| May 22 | Capital of Colombia | Bogotá |
| May 22 | Capital of Burkina Faso | Ouagadougou |

| May 22 | The Big Valley | Victoria Barkley | Barbara Stanwyck |
| May 22 | The Donna Reed Show | Donna Stone | Donna Reed |
| May 22 | Route 66 | Tod Stiles | Martin Milner |
| May 22 | Petticoat Junction | Kate Bradley | Bea Benaderet |
| May 22 | The Saint | Simon Templar | Roger Moore |
| May 22 | The Facts of Life | Edna Garrett | Charlotte Rae |

| May 22 | Amy Tan — 1989 SF immigrant mothers/daughters novel | The Joy Luck Club |
| May 22 | Frank Herbert — 1965 desert-planet sci-fi epic | Dune |
| May 22 | "And miles to go before I sleep" closes which Frost poem | Stopping by Woods on a Snowy Evening |
| May 22 | French sculptor of "The Thinker" / "The Kiss" | Auguste Rodin |
| May 22 | American Pop artist of Ben-Day dot comic-strip paintings | Roy Lichtenstein |
| May 22 | German Romantic composer of Lullaby/Wiegenlied + German Requiem | Johannes Brahms |

| May 22 | Sears, Roebuck founded year/founders | 1893, Richard Sears + Alvah Roebuck, Chicago |
| May 22 | Edison practical incandescent bulb patent year | 1879 (US Patent 223,898) |
| May 22 | Chocolate chip cookie inventor & inn name | Ruth Wakefield, 1938, Toll House Inn (Whitman MA) |
| May 22 | Marriott founded year / humble origin | 1927, J. Willard Marriott — A&W root beer stand in DC |
| May 22 | Insulin isolated year/team | 1921, Banting & Best, U. of Toronto |
| May 22 | Salk polio vaccine declared safe date | April 12, 1955 (announced from U. Michigan) |

| May 22 | Geography | Greenland is world's largest island (~836,330 sq mi); not a continent |
| May 22 | Geography | Dead Sea shore — lowest dry land on Earth (~1,410 ft below sea level) |
| May 22 | Botany | Hyperion (CA coast redwood) tallest tree ~380 ft; discovered 2006 |
| May 22 | History | Iceland's Althing (930 AD) oldest continuously functioning legislature |
| May 22 | Animals | Group of crocodiles = "float" (water) or "bask" (land); can stay submerged 1+ hour |
| May 22 | Law/Food | Nix v. Hedden (1893) — tomato ruled a vegetable for US tariffs |
| May 22 | Astronomy | Mercury (not Venus) is on average closest planet to Earth (mathematical curiosity) |
| May 22 | Tech | First text message Dec 3, 1992 — "Merry Christmas" via Vodafone (Neil Papworth) |
| May 22 | Animals | Bald eagle nests can weigh 2+ tons; largest ~2.7 tons in Florida |
| May 22 | Animals | Wolverine = largest land mustelid (weasel family), not a bear |
| May 22 | Etymology | "Banana republic" coined by O. Henry — Cabbages and Kings (1904) |
| May 22 | Animals | Blue whale tongue weighs like an elephant; heart size of small car |
| May 22 | Sports | Reds 26-24 .520 T-4th NL Central 4.5 GB Brewers (29-18); STL game today PPD rain; doubleheader Sat 5/23 |
| May 22 | Sports | NBA: Knicks 2-0 over Cavs (G2 109-93 Thu); Spurs/Thunder 1-1, G3 Fri 8:30 ET |
| May 22 | Sports | NHL Conf Finals: Vegas 1-0 Avs (G2 Fri); Hurricanes-Habs E G1 Thu (CAR 8-0 PO entering) |
| May 22 | NASCAR | Kyle Busch dies at 41 May 21 — Coca-Cola 600 weekend |
| May 22 | NFL | Rodgers reports to Steelers OTAs day one; first OTA pass to Michael Pittman Jr. |
| May 22 | Box Office | Michael $26.1M #1 4th wknd; Prada 2 $17.8M; Obsession $17.1M open; Mandalorian & Grogu opens 5/22 ($12M previews, $80M 3-day proj) |

| May 22 | May 22 (Great Chilean Earthquake 1960 — 9.5 strongest ever; Apollo 10 LM 8.4 nm from Moon 1969; Joplin EF5 tornado 2011 — 158 killed) | — |
| May 22 | National Days: National Maritime Day; International Day for Biological Diversity (UN); National Road Trip Day; Bitcoin Pizza Day; National Vanilla Pudding Day; Harvey Milk Day; National Don't Fry Day | — |

| May 22 | California Love | 2Pac feat. Dr. Dre & Roger Troutman | 1995 |
| May 22 | November Rain | Guns N' Roses | 1991 |
| May 22 | Killing In The Name | Rage Against the Machine | 1992 |
| May 22 | No Diggity | Blackstreet feat. Dr. Dre & Queen Pen | 1996 |
| May 22 | SexyBack | Justin Timberlake feat. Timbaland | 2006 |
| May 22 | Welcome to the Black Parade | My Chemical Romance | 2006 |

_Last updated: May 22, 2026 (v14 — May 22 Friday run added)_

| May 25 | Capital of Serbia | Belgrade |
| May 25 | Capital of Mozambique | Maputo |
| May 25 | Capital of Kyrgyzstan | Bishkek |
| May 25 | Capital of Oman | Muscat |

| May 25 | Airwolf | Stringfellow Hawke | Jan-Michael Vincent |
| May 25 | The Rifleman | Lucas McCain | Chuck Connors |
| May 25 | Doogie Howser, M.D. | Doogie Howser | Neil Patrick Harris |
| May 25 | Perfect Strangers | Balki Bartokomous | Bronson Pinchot |
| May 25 | Scarecrow and Mrs. King | Lee Stetson | Bruce Boxleitner |
| May 25 | McCloud | Marshal Sam McCloud | Dennis Weaver |

| May 25 | Douglas Adams — "Answer to Life" from Hitchhiker's Guide | 42 |
| May 25 | Only major female French Impressionist — mother/children paintings | Mary Cassatt |
| May 25 | Paul Gauguin relocated to which island to paint | Tahiti (French Polynesia) |
| May 25 | Middlemarch author / real name | George Eliot (Mary Ann Evans) |
| May 25 | Roald Dahl children's novels | James and the Giant Peach / Charlie and the Chocolate Factory |
| May 25 | "Water water everywhere" poem / poet | The Rime of the Ancient Mariner / Samuel Taylor Coleridge |

| May 25 | Guinness Brewery founding year (9,000-yr lease) | 1759 |
| May 25 | Marconi transatlantic radio signal destination province | Newfoundland (Signal Hill, St. John's) |
| May 25 | X-rays named "X" because | Unknown nature of the radiation (X = unknown) |
| May 25 | Red Bull inspired by drink from which country | Thailand (Krating Daeng) |
| May 25 | Converse Chuck Taylors original sport | Basketball (1917) |
| May 25 | ByteDance Chinese domestic version of TikTok | Douyin |

| May 25 | Animals | Wombats only animals with cube-shaped droppings — prevents rolling off logs/rocks |
| May 25 | Food/Culture | Fortune cookies invented in San Francisco (Japanese-American immigrants), not China |
| May 25 | Astronomy | Earth has ~3 trillion trees — more than stars in the Milky Way (~100-400 billion) |
| May 25 | Geography | Canary Islands named after dogs (Insula Canaria = Island of Dogs), not the bird |
| May 25 | Science | Eiffel Tower grows ~6 inches (15 cm) taller in summer due to thermal expansion |
| May 25 | Biology | Humans only mammals with true protruding chin bone |
| May 25 | Records | Charles Osborne hiccuped for 68 years (1922-1990) — Guinness record |
| May 25 | History | First US televised baseball game = Reds vs. Dodgers, August 26, 1939, NBC W2XBS |
| May 25 | Animals | Flamingos naturally white/gray; pink color from carotenoids in their diet |
| May 25 | Geography | Maine only US state with one-syllable name; borders only one other state (NH) |
| May 25 | Math | 52! deck arrangements (~8×10^67) > atoms on Earth; every shuffle is likely unique |
| May 25 | Weather | UK hottest May day in 79 years: 32.3°C at Kew Gardens, London (this week) |

| May 25 | May 25 (Babe Ruth 714th/last HR at Forbes Field 1935; JFK moon challenge 1961; Star Wars release 1977 — 49th anniversary; AA Flt 191 O'Hare crash 1979 — 273 killed; Phoenix Mars lander touchdown 2008) | — |
| May 25 | National Days: Memorial Day; National Wine Day; Geek Pride Day; Towel Day (Douglas Adams); National Tap Dance Day; African Liberation Day | — |

_Last updated: May 25, 2026 (v15 — May 25 Memorial Day run added)_

| May 27 | Capital of Ecuador | Quito |
| May 27 | Capital of Slovakia | Bratislava |
| May 27 | Capital of Tajikistan | Dushanbe |
| May 27 | Capital of Belize | Belmopan |

| May 27 | Spenser: For Hire | Spenser | Robert Urich |
| May 27 | Gimme a Break! | Nell Harper | Nell Carter |
| May 27 | The White Shadow | Ken Reeves | Ken Howard |
| May 27 | Medical Center | Dr. Joe Gannon | Chad Everett |
| May 27 | Alias Smith and Jones | Hannibal Heyes / Kid Curry | Pete Duel / Ben Murphy |
| May 27 | Mr. Belvedere | George Belvedere | Christopher Hewett |

| May 27 | Thomas Hardy — Dorset county fictional name | Wessex |
| May 27 | Hermann Hesse — 1946 Nobel Prize novel | The Glass Bead Game (Magister Ludi) |
| May 27 | Aleksandr Solzhenitsyn Nobel Prize year | 1970 |
| May 27 | Jean Sibelius — Finnish anthem connection | Finlandia (1899) |
| May 27 | George Bernard Shaw — refused which honor in 1925 | Nobel Prize (accepted only Nobel Medal) |
| May 27 | Kazuo Ishiguro — 2017 Nobel Prize; key novel | The Remains of the Day |

| May 27 | Home Depot | 1978 (Atlanta founders: Blank, Marcus, Langone) |
| May 27 | Blockbuster | 1985 (Dallas, David Cook) |
| May 27 | Cotton candy machine | 1897 (William Morrison & John Wharton) |
| May 27 | TikTok | 2016 (ByteDance, Zhang Yiming) |
| May 27 | Zoom | 2011 (Eric Yuan; launched 2013) |
| May 27 | Leatherman multi-tool | 1983 (Tim Leatherman) |

| May 27 | History | William Henry Harrison shortest presidency — died pneumonia 31 days (1841) |
| May 27 | History | US 50-star flag designed by 17-yr-old Robert Heft as school project (got B-, then A after Congress adopted it) |
| May 27 | Animals | Group of peacocks called a muster (males) or bevy (females) |
| May 27 | Astronomy | Jupiter's Great Red Spot is a storm that has lasted 350+ years |
| May 27 | Science | Tardigrades (water bears) survive in space, extreme heat/cold, radiation |
| May 27 | Food | Nutella invented in WWII — cocoa scarce, hazelnuts used to stretch supply |
| May 27 | Geography | Welsh village Llanfairpwllgwyngyllgogerychwyrndrobwllllantysiliogogogoch — 58 letters, longest place name in Europe |
| May 27 | History | Typewriter (1868) invented before telephone (1876) |
| May 27 | Geography | Norway's coastline (58,000 mi) longer than equator (24,901 mi) |
| May 27 | History | Green Sahara existed 5,000-11,000 years ago; hippos and crocs in current desert regions |
| May 27 | Science | Human brain uses ~20 watts of power — enough to power a dim light bulb |

| May 27 | Sports | NBA Finals: Knicks vs. Pacers (East) — Knicks first Finals since 1999; Thunder beat Spurs for West |
| May 27 | Sports | NHL: Conf Finals — VGK (West) vs. ? (East); CAR leads MTL 2-1 tonight G4 |
| May 27 | Sports | MLS: Lionel Messi 13G/6A for Inter Miami 2026 |
| May 27 | Sports | NFL: Aaron Rodgers reports to Pittsburgh Steelers OTAs |
| May 27 | Deaths | Kyle Busch (41), NASCAR champion, died May 21 |
| May 27 | Deaths | Doris Fisher (94), co-founder Gap Inc., died May 2026 |
| May 27 | Deaths | Alex Ligertwood (79), lead vocalist for Santana, died May 2026 |
| May 27 | Box Office | Mandalorian & Grogu #1 opening wknd $100M domestic 4-day / $163M global |
| May 27 | Box Office | Michael (Michael Jackson biopic) approaching $800M WW |

| May 27 | May 27 (St. Petersburg founded by Peter the Great 1703; Chrysler Building opened NYC 1930; Golden Gate Bridge Pedestrian Day 1937) | — |
| May 27 | National Days: National Sunscreen Day; World Otter Day; National Flip Flop Day; Eid ul-Adha | — |

| May 27 | In the End | Linkin Park | 2000 |
| May 27 | Semi-Charmed Life | Third Eye Blind | 1997 |
| May 27 | Santeria | Sublime | 1996 |
| May 27 | Beautiful | Christina Aguilera | 2002 |
| May 27 | Lightning Crashes | Live | 1994 |

_Last updated: May 27, 2026 (v16 — May 27 Wednesday run added)_

| May 28 | Capital of Austria | Vienna |
| May 28 | Capital of the Philippines | Manila |
| May 28 | Capital of Colombia | Bogotá |
| May 28 | Capital of Romania | Bucharest |

| May 28 | Mission: Impossible | Jim Phelps | Peter Graves |
| May 28 | The Mod Squad | Linc Hayes | Clarence Williams III |
| May 28 | Roseanne | Roseanne Conner | Roseanne Barr |
| May 28 | Home Improvement | Tim "The Toolman" Taylor | Tim Allen |
| May 28 | Night Court | Judge Harry T. Stone | Harry Anderson |
| May 28 | NYPD Blue | Det. Andy Sipowicz | Dennis Franz |

| May 28 | "Call me Ishmael" opening line novel / author | Moby-Dick / Herman Melville |
| May 28 | Author of Don Quixote | Miguel de Cervantes (1605) |
| May 28 | Toni Morrison debut novel | The Bluest Eye (1970) |
| May 28 | William Faulkner fictional Mississippi county | Yoknapatawpha County |
| May 28 | Beethoven 9th Symphony premiere year (while deaf) | 1824 |
| May 28 | "Do not go gentle into that good night" poet | Dylan Thomas |

| May 28 | McDonald's founded year / founders | 1940 / Dick & Mac McDonald |
| May 28 | World Wide Web inventor / year | Tim Berners-Lee / 1989 (CERN) |
| May 28 | Amazon founded year | 1994 (Jeff Bezos, Bellevue WA) |
| May 28 | LEGO founding year / country | 1932 / Denmark (Ole Kirk Christiansen) |
| May 28 | Polio vaccine developer / year | Jonas Salk / 1955 |
| May 28 | Post-it Note inventor / what Silver tried to invent | Spencer Silver (strong adhesive, got weak one) → Art Fry applied 1974 → launched 1980 |

| May 28 | Animals | Octopuses have 3 hearts and blue blood (copper-based hemocyanin) |
| May 28 | Science | Lightning ~5× hotter than sun's surface (~30,000K vs 5,500K) |
| May 28 | History | Napoleon was average height ~5'7" — myth from British propaganda + measurement confusion |
| May 28 | Food | Honey never spoils — 3,000-yr-old edible honey found in Egyptian tombs |
| May 28 | Geography | Canada has more lakes than rest of world combined (~60% of world's freshwater lakes) |
| May 28 | History | Oxford Univ (teaching ~1096 AD) older than Aztec Empire (founded ~1345 AD) |
| May 28 | Animals | Crows recognize individual human faces and hold grudges |
| May 28 | Science | Water boils at 202°F/94°C atop Mt. Everest (lower atmospheric pressure) |
| May 28 | Geography | Vatican City world's smallest country (~110 acres, ~size of golf course) |
| May 28 | Language | "Queue" sounds same with last 4 letters removed |

| May 28 | NBA Finals | Knicks in Finals (first since 1999); West Finals G6 TONIGHT Thunder vs Spurs OKC 3-2 |
| May 28 | NHL | VGK swept COL — in Stanley Cup Finals; CAR leads MTL 3-1 East Final |
| May 28 | Deaths | Sonny Rollins (95), jazz saxophonist, died May 25 |
| May 28 | Deaths | Rob Base (59), rapper "It Takes Two", died May 22 |
| May 28 | Deaths | Pierre Deny (69), Emily in Paris actor, died May 25 ALS |
| May 28 | Box Office | Mandalorian & Grogu still #1; Martin Scorsese voices Hugo alien fry cook |

| May 28 | May 28 (Volkswagen founded 1937 — 89th birthday; Dionne quintuplets born 1934; Belgium surrendered WWII 1940; Maya Angelou died 2014) | — |
| May 28 | National Days: National Hamburger Day; Amnesty International Day; World Hunger Day; International Day of Action on Women's Health | — |

| May 28 | Mr. Jones | Counting Crows | 1993 |
| May 28 | Iris | The Goo Goo Dolls | 1998 |
| May 28 | Drops of Jupiter | Train | 2001 |
| May 28 | Don't Speak | No Doubt | 1996 |
| May 28 | Black Hole Sun | Soundgarden | 1994 |

_Last updated: May 28, 2026 (v17 — May 28 Thursday run added)_

| Jun 1 | Capital of Ohio | Columbus |
| Jun 1 | Capital of Canada | Ottawa |
| Jun 1 | Capital of Kenya | Nairobi |
| Jun 1 | Capital of Poland | Warsaw |

| Jun 1 | Have Gun – Will Travel | Paladin | Richard Boone |
| Jun 1 | The Avengers (1961 UK) | John Steed | Patrick Macnee |
| Jun 1 | Kung Fu | Kwai Chang Caine | David Carradine |
| Jun 1 | Soap | Jessica Tate | Katherine Helmond |
| Jun 1 | The Love Boat | Capt. Merrill Stubing | Gavin MacLeod |
| Jun 1 | Falcon Crest | Angela Channing | Jane Wyman |

| Jun 1 | Author of Fahrenheit 451 (1953) | Ray Bradbury |
| Jun 1 | Author of The Handmaid's Tale (1985) | Margaret Atwood |
| Jun 1 | Dutch painter of The Garden of Earthly Delights | Hieronymus Bosch |
| Jun 1 | French composer of Clair de Lune | Claude Debussy |
| Jun 1 | Beat poet who wrote Howl (1956) | Allen Ginsberg |
| Jun 1 | Author of Pulitzer-winning The Road | Cormac McCarthy |

| Jun 1 | Ben & Jerry's founded | 1978, Burlington, Vermont (Ben Cohen & Jerry Greenfield) |
| Jun 1 | Tesla Inc. founders/year | 2003, Martin Eberhard & Marc Tarpenning |
| Jun 1 | Movable-type printing press inventor | Johannes Gutenberg (~1440) |
| Jun 1 | Spotify founded | 2006, Stockholm, Sweden (Daniel Ek & Martin Lorentzon) |
| Jun 1 | Häagen-Dazs origin | 1960, the Bronx NYC; name is made-up "Danish-sounding" nonsense |
| Jun 1 | Disposable safety razor patent | 1904, King C. Gillette |

| Jun 1 | Geography | Istanbul is the only major city spanning two continents (Europe & Asia) |
| Jun 1 | Astronomy | A day on Mercury (sunrise to sunrise) ~176 Earth days — longer than its 88-day year |
| Jun 1 | Animals | A group of jellyfish is called a "smack" |
| Jun 1 | History | The Hundred Years' War actually lasted 116 years (1337–1453) |
| Jun 1 | Language | "OK" first appeared in print in 1839 Boston as a joke for "oll korrect" |
| Jun 1 | Geography | Africa is the only continent in all four hemispheres (N, S, E, W) |
| Jun 1 | Animals | Starfish have no brain and no blood; move via water-vascular system |
| Jun 1 | Science | Human body contains enough carbon to make ~900 pencils |
| Jun 1 | Pop culture | Hollywood sign originally read "HOLLYWOODLAND" (erected 1923) |
| Jun 1 | Food | Pineapple enzyme bromelain digests protein — makes tongue tingle |
| Jun 1 | Sports | Golf balls have 300–500 dimples; fly ~2x farther than a smooth ball |
| Jun 1 | Time | In medieval England a "moment" was exactly 90 seconds |

| Jun 1 | Sports | Reds 30-29, 5th NL Central 7.0 GB; lost to Royals 9-2 (Jun 1); 1-4 last 5 |
| Jun 1 | NBA | Finals set: Knicks vs Spurs (1999 rematch); Knicks' first Finals since '99; Wembanyama for SA; G1 Jun 3 |
| Jun 1 | NHL | Stanley Cup Final: Golden Knights vs Hurricanes; Vegas swept Presidents'-Trophy Avalanche; G1 Jun 2 |
| Jun 1 | MLS | Messi (L hamstring fatigue) & De Paul named to Argentina's 26-man World Cup roster; Messi joins billionaire club |
| Jun 1 | NFL | OTAs underway: Mahomes back in drills (ACL rehab), Lamar Jackson returns to Ravens, Rodgers with Steelers |
| Jun 1 | World Cup | 2026 FIFA World Cup kicks off Jun 11 — first 48-team, 3-nation (USA/Can/Mex), 16 host cities, final Jul 19 |
| Jun 1 | Box Office | Backrooms (A24) #1: $81.4M dom / $117.9M WW opening — A24 record; dir Kane Parsons (20) youngest ever #1 |
| Jun 1 | Deaths | Bob Horner (68, Braves 3B/1978 NL ROY); Claude Lemieux (60, 4x Cup champ, 1995 Conn Smythe); Kelly Curtis (69, actress, Jamie Lee Curtis's sister); Jay Daniel (82, TV producer Moonlighting/Roseanne); Marc Johnson (49, pro skateboarder) |

| Jun 1 | June 1 (CNN launches as first 24-hr news channel 1980; Beatles release Sgt. Pepper 1967; Helen Keller dies 1968; James Clark Ross reaches North Magnetic Pole 1831) | — |
| Jun 1 | National Days: World Milk Day; National Pen Pal Day; National Olive Day; Dinosaur Day; World Reef Awareness Day; National Go Barefoot Day; International Children's Day; National Say Something Nice Day | — |

| Jun 1 | Bittersweet Symphony | The Verve | 1997 |
| Jun 1 | Mr. Brightside | The Killers | 2004 |
| Jun 1 | Clocks | Coldplay | 2002 |
| Jun 1 | Seven Nation Army | The White Stripes | 2003 |
| Jun 1 | 1979 | The Smashing Pumpkins | 1996 |
| Jun 1 | Boulevard of Broken Dreams | Green Day | 2004 |

_Last updated: June 1, 2026 (v18 — June 1 run added; music links use Spotify/Apple search URLs)_

| Jun 2 | Capital of Tunisia | Tunis |
| Jun 2 | Capital of Wales | Cardiff |
| Jun 2 | Capital of Lebanon | Beirut |
| Jun 2 | Capital of Venezuela | Caracas |

| Jun 2 | The Phil Silvers Show | Sgt. Ernie Bilko | Phil Silvers |
| Jun 2 | Sea Hunt | Mike Nelson | Lloyd Bridges |
| Jun 2 | Ironside | Chief Robert T. Ironside | Raymond Burr |
| Jun 2 | Cannon | Frank Cannon | William Conrad |
| Jun 2 | Trapper John, M.D. | "Trapper John" McIntyre | Pernell Roberts |
| Jun 2 | Alice | Alice Hyatt | Linda Lavin |

| Jun 2 | Author of Gulliver's Travels (1726) | Jonathan Swift |
| Jun 2 | Author of The Canterbury Tales | Geoffrey Chaucer |
| Jun 2 | Author of Robinson Crusoe (1719) | Daniel Defoe |
| Jun 2 | Author of The War of the Worlds (1898) | H.G. Wells |
| Jun 2 | Flemish Baroque painter of The Descent from the Cross | Peter Paul Rubens |
| Jun 2 | Composer of The Carnival of the Animals | Camille Saint-Saëns |

| Jun 2 | Bagless cyclonic vacuum / prototypes | James Dyson — 5,127 prototypes |
| Jun 2 | Super Soaker inventor | Lonnie Johnson (NASA engineer), 1989 |
| Jun 2 | Bluetooth named after | King Harald "Bluetooth" Gormsson (10th-c. Denmark) |
| Jun 2 | Stethoscope inventor/year | René Laennec, 1816 |
| Jun 2 | Modern trampoline inventor/year | George Nissen, 1936 |
| Jun 2 | Braille reading system | Louis Braille, 1824 (at age 15) |

| Jun 2 | Astronomy | Neutron star: sugar-cube-sized piece weighs ~1 billion tons |
| Jun 2 | Animals | A shrimp's heart is in its head |
| Jun 2 | Geography | Russia spans 11 time zones — more than any country |
| Jun 2 | Language | "Set" has the most distinct dictionary definitions (400+) |
| Jun 2 | History | Cleopatra lived closer to the Moon landing than to the Great Pyramid's construction |
| Jun 2 | Food | Carrots were originally purple; orange bred in 17th-c. Netherlands |
| Jun 2 | Science | Mpemba effect — hot water can freeze faster than cold |
| Jun 2 | Animals | Octopuses taste with their arms (chemical receptors in suckers) |
| Jun 2 | Body | Human nose can detect ~1 trillion distinct scents |
| Jun 2 | Pop culture | "Star-Spangled Banner" set to an 18th-c. British drinking song |
| Jun 2 | Geography | The Sahara (Ain Sefra, Algeria) has been dusted with snow multiple times in the last decade |
| Jun 2 | Animals | Honeybees recognize human faces by combining features |

| Jun 2 | Sports | Reds 30-29 .508 5th NL Central 7.0 GB Brewers (36-21); last 5 L-L-L-W-L (1-4); vs KC Royals today 7:10 ET (lost opener 9-2) |
| Jun 2 | NHL | Stanley Cup Final Game 1 tonight Jun 2 — Golden Knights @ Hurricanes 8 ET ABC; Vegas swept Avalanche |
| Jun 2 | NBA | Finals Knicks vs Spurs (1999 rematch); G1 Wed Jun 3 8:30 ET ABC; Wembanyama for SA |
| Jun 2 | MLS | Messi & De Paul named to Argentina 26-man World Cup roster |
| Jun 2 | NFL | OTAs continue: Mahomes (ACL rehab), Lamar Jackson (Ravens), Rodgers (Steelers) |
| Jun 2 | Box Office | Backrooms (A24) still #1, past $89M dom / $120M+ WW in 4 days; Obsession +39% 2nd weekend ($23.9M); dir Kane Parsons (20) youngest #1 ever |
| Jun 2 | Deaths | Rick Adelman (79, HOF NBA coach); Raymond Berry (93, NFL HOF WR Colts); Joe Negri (99, Mr Rogers "Handyman Negri"); Foster Sylvers (64, 1970s R&B "Misdemeanor") |

| Jun 2 | June 2 (QEII coronation 1953 — first televised major intl event; Indian Citizenship Act 1924; Surveyor 1 first US Moon soft-landing 1966; Lou Gehrig dies 1941) | — |
| Jun 2 | National Days: National Rotisserie Chicken Day; National Rocky Road Day; American Indian Citizenship Day; National Leave Work Early Day; National First Ladies Day; Italy Festa della Repubblica | — |

| Jun 2 | Song 2 | Blur | 1997 |
| Jun 2 | Buddy Holly | Weezer | 1994 |
| Jun 2 | Kryptonite | 3 Doors Down | 2000 |
| Jun 2 | My Own Worst Enemy | Lit | 1999 |
| Jun 2 | All Star | Smash Mouth | 1999 |
| Jun 2 | Sabotage | Beastie Boys | 1994 |

_Last updated: June 2, 2026 (v19 — June 2 Tuesday run added)_

| Jun 3 | Capital of Nebraska | Lincoln |
| Jun 3 | Capital of Idaho | Boise |
| Jun 3 | Capital of Zimbabwe | Harare |
| Jun 3 | Capital of Paraguay | Asunción |
| Jun 3 | Capital of Malta | Valletta |

| Jun 3 | My Favorite Martian | Uncle Martin | Ray Walston |
| Jun 3 | Baretta | Tony Baretta | Robert Blake |
| Jun 3 | Benson | Benson DuBois | Robert Guillaume |
| Jun 3 | The Greatest American Hero | Ralph Hinkley | William Katt |
| Jun 3 | Matlock | Ben Matlock | Andy Griffith |
| Jun 3 | Touched by an Angel | Monica | Roma Downey |

| Jun 3 | Author of The Count of Monte Cristo | Alexandre Dumas |
| Jun 3 | Baroque chiaroscuro painter, The Calling of St. Matthew | Caravaggio |
| Jun 3 | Composer of Flight of the Bumblebee | Nikolai Rimsky-Korsakov |
| Jun 3 | A Raisin in the Sun playwright | Lorraine Hansberry |
| Jun 3 | The Good Earth (Pulitzer 1932) | Pearl S. Buck |
| Jun 3 | Peter Pan author (rights to Great Ormond Street) | J.M. Barrie |

| Jun 3 | Samsung founded 1938 as | Grocery/dried-fish trader, Korea |
| Jun 3 | Nokia founded 1865 as | Paper mill, Finland |
| Jun 3 | Lamborghini founder's prior business | Tractors (Ferruccio Lamborghini, 1963) |
| Jun 3 | 7-Eleven origin 1927 | Southland Ice Company, Dallas |
| Jun 3 | Vaseline patent 1872 | Robert Chesebrough (ate a spoonful daily) |
| Jun 3 | First crossword puzzle 1913 | Arthur Wynne, New York World |

| Jun 3 | Animals | Nine-banded armadillos always birth identical quadruplets |
| Jun 3 | History | France still used the guillotine when Star Wars premiered (last use Sept 1977) |
| Jun 3 | Geography | Philippines ~7,641 islands, only ~2,000 inhabited |
| Jun 3 | Animals | Kangaroos can't walk backwards (coat of arms symbolism) |
| Jun 3 | Language | "Nerd" first appeared in Dr. Seuss's If I Ran the Zoo (1950) |
| Jun 3 | Language | # symbol = "octothorpe" (Bell Labs, 1960s) |
| Jun 3 | History | Abraham Lincoln was a licensed bartender (Berry & Lincoln, 1833) |
| Jun 3 | Food | Croissant descends from Austrian kipferl, not French |
| Jun 3 | Space | Apollo astronauts signed insurance autograph covers for families |
| Jun 3 | Science | Regular soda sinks in water; diet soda floats (sugar density) |

| Jun 3 | Sports | Reds 31-29 .517 5th NL Central 7.0 GB; last 5 W-L-W-L-L (2-3); vs KC Royals today 7:10 ET |
| Jun 3 | NBA | Finals G1 tonight: Knicks @ Spurs 8:30 ET (NY first Finals since 1999) |
| Jun 3 | NHL | SCF G1: Vegas won 5-4 @ Carolina (Hertl GWG); G2 Thu Jun 4 ABC |
| Jun 3 | MLB | C. Sánchez 44.2 IP scoreless streak; Mariners 8-game W streak; Ohtani 0.82 ERA; ASG voting open (Jul 14 PHL) |
| Jun 3 | NFL | OTAs: Rodgers $25M farewell yr PIT; Mahomes ACL rehab drills; Robertson-Harris (NYG) out for season |
| Jun 3 | World Cup | Opens Jun 11 Mexico v South Africa, Estadio Azteca; 48 teams, 3 hosts |
| Jun 3 | Box Office | Backrooms #1, $81M opening / $118M WW, A24 record, crosses $100M in 6 days; ~$10M budget |
| Jun 3 | Deaths | Peabo Bryson (75, R&B Grammy duets); Rick Adelman (79, NBA coach); Bob Horner (68, Braves) |

| Jun 3 | June 3 (Ed White first US spacewalk 1965; "Casey at the Bat" published 1888; John Adams first president in DC 1800) | — |
| Jun 3 | National Days: World Bicycle Day; Global Running Day; National Egg Day; National Repeat Day | — |

| Jun 3 | Closing Time | Semisonic | 1998 |
| Jun 3 | Two Princes | Spin Doctors | 1991 |
| Jun 3 | What's Up? | 4 Non Blondes | 1992 |
| Jun 3 | I Try | Macy Gray | 1999 |
| Jun 3 | The Middle | Jimmy Eat World | 2001 |
| Jun 3 | Apologize | Timbaland ft. OneRepublic | 2007 |

_Last updated: June 3, 2026 (v20 — June 3 Wednesday run added)_

| Jun 5 | Capital of Iraq | Baghdad |
| Jun 5 | Capital of Bulgaria | Sofia |
| Jun 5 | Capital of Armenia | Yerevan |
| Jun 5 | Capital of Laos | Vientiane |

| Jun 5 | T.J. Hooker | Sgt. T.J. Hooker | William Shatner |
| Jun 5 | The Fall Guy | Colt Seavers | Lee Majors |
| Jun 5 | Buck Rogers in the 25th Century | Buck Rogers | Gil Gerard |
| Jun 5 | 77 Sunset Strip | Stu Bailey | Efrem Zimbalist Jr. |
| Jun 5 | McHale's Navy | Lt. Cmdr. Quinton McHale | Ernest Borgnine |
| Jun 5 | Burke's Law | Amos Burke | Gene Barry |

| Jun 5 | First African Nobel Literature laureate (1986, Nigeria) | Wole Soyinka |
| Jun 5 | "Father of Modern Art" / The Card Players | Paul Cézanne |
| Jun 5 | Piano Concerto No. 2 in C minor (1901) | Sergei Rachmaninoff |
| Jun 5 | Philip K. Dick novel that became Blade Runner | Do Androids Dream of Electric Sheep? (1968) |
| Jun 5 | Author of Gone with the Wind (Pulitzer 1937) | Margaret Mitchell |
| Jun 5 | Flemish painter of the Arnolfini Portrait (1434) | Jan van Eyck |

| Jun 5 | Taco Bell founded year/founder | 1962, Glen Bell, Downey CA |
| Jun 5 | Rolls-Royce founders (1906) | Henry Royce & Charles Rolls, Manchester |
| Jun 5 | Heineken founded year/founder/city | 1873, Gerard Adriaan Heineken, Amsterdam |
| Jun 5 | Porsche founded year/founder | 1931, Ferdinand Porsche, Stuttgart |
| Jun 5 | First public telegraph message (1844) | "What hath God wrought" — Samuel Morse |
| Jun 5 | Dunkin' founded year/city | 1950, Bill Rosenberg, Quincy MA |

| Jun 5 | History | Great Emu War 1932 — Australian military vs. emus; emus won |
| Jun 5 | History | New Zealand first country to grant women's suffrage (1893) |
| Jun 5 | Sports/History | Abraham Lincoln — near-undefeated wrestler; National Wrestling Hall of Fame |
| Jun 5 | Animals | Group of turkeys = "rafter"; group of kangaroos = "mob" |
| Jun 5 | History | Leaning Tower of Pisa took 177 years to build (1173–1350) |
| Jun 5 | History | Swiss neutrality formalized at Congress of Vienna (1815) |
| Jun 5 | Animals | Flea jumps ~200× its own body length |
| Jun 5 | History | Roman Colosseum flooded for mock naval battles — "naumachiae" |
| Jun 5 | Tech | Anthropic files for IPO; valuation ~$965B |
| Jun 5 | Sports | NBA Finals: Knicks vs. Spurs (1999 rematch); G1 Knicks 105-95; G2 tonight |
| Jun 5 | Sports | NHL SCF: Vegas 1 CAR 1 (G2 CAR won 4-3 OT); G3 Sat Jun 6 |
| Jun 5 | Sports | Reds 31-30 .508 5th NL Central 6.5 GB Brewers (37-23); @ STL 8:15 PM ET |
| Jun 5 | Sports | FIFA World Cup 2026 opens Jun 11 — first 48-team / 3-nation WC; Mexico vs South Africa at Azteca |
| Jun 5 | Box Office | Scary Movie 6 #1 ~$52M+ opening — franchise record; Masters of Universe #2 ~$31M |
| Jun 5 | Deaths | Anthony Head (72, Giles on Buffy/Ted Lasso); Marjane Satrapi (56, Persepolis); Peabo Bryson (75, R&B duets); James Handy (81, character actor) |
| Jun 5 | News | Senate $70B immigration bill; Iran missiles vs Kuwait/Bahrain; Anthropic IPO filing; Scott Pelley vs. CBS |

| Jun 5 | One | U2 | 1991 |
| Jun 5 | Basket Case | Green Day | 1994 |
| Jun 5 | The Sign | Ace of Base | 1993 |
| Jun 5 | Independent Women Pt. 1 | Destiny's Child | 2000 |
| Jun 5 | Low (feat. T-Pain) | Flo Rida | 2007 |

| Jun 5 | June 5 (Marshall Plan announced 1947; RFK shot 1968; Apple II on sale 1977; first AIDS report 1981; Reagan dies 2004) | — |
| Jun 5 | National Days: World Environment Day; National Doughnut Day; National Hot Air Balloon Day; National Cheese Day; National Gingerbread Day | — |

_Last updated: June 5, 2026 (v21 — June 5 Thursday run added)_

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


_Last updated: June 12, 2026 (v25 — June 12 Friday run added)_
