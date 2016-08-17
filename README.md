# PokeData

[![Join the chat at https://gitter.im/pokemongoers/PokeData](https://badges.gitter.im/pokemongoers/PokeData.svg)](https://gitter.im/pokemongoers/PokeData?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
 In this project you will scrape as much data as you can get about the *actual* sightings of Pokemons. As it turns out, players all around the world started reporting sightings of Pokemons and are logging them into a central repository (i.e. a database). We want to get this data so we can train our machine learning models. You will of course need to come up with other data sources not only for sightings but also for other relevant details that can be used later on as features for our machine learning algorithm (see Project B). Additional features could be air temperature during the given timestamp of sighting, location close to water, buildings or parks. Consult with Pokemon Go expert if you have such around you and come up with as many features as possible that describe a place, time and name of a sighted Pokemon. Another feature that you will implement is a twitter listener: You will use the twitter streaming API (https://dev.twitter.com/streaming/public) to listen on a specific topic (for example, the #foundPokemon hashtag). When a new tweet with that hashtag is written, an event will be fired in your application checking the details of the tweet, e.g. location, user, time stamp. Additionally, you will try to parse formatted text from the tweets to construct a new “seen” record that consequently will be added to the database. Some of the attributes of the record will be the Pokemon's name, location and the time stamp. Additional data sources (here is one: https://pkmngowiki.com/wiki/Pok%C3%A9mon) will also need to be integrated to give us more information about Pokemons e.g. what they are, what’s their relationship, what they can transform into, which attacks they can perform etc.