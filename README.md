# Finding-Movie-Similarity-from-Plot-Summaries

<p>We all love watching movies! There are some movies we like, some we don't. Most people have a preference for movies of a similar genre. Some of us love watching action movies, while some of us like watching horror. Some of us like watching movies that have ninjas in them, while some of us like watching superheroes.</p>
<p>Movies within a genre often share common base parameters. Consider the following two movies:</p>
<p><img style="margin:5px 20px 5px 1px; height: 250px; display: inline-block;" alt="2001: A Space Odyssey" src="https://assets.datacamp.com/production/project_648/img/movie1.jpg">
<img style="margin:5px 20px 5px 1px; height: 250px; display: inline-block;" alt="Close Encounters of the Third Kind" src="https://assets.datacamp.com/production/project_648/img/movie2.jpg"></p>
<p>Both movies, <em>2001: A Space Odyssey</em> and <em>Close Encounters of the Third Kind</em>, are movies based on aliens coming to Earth. I've seen both, and they indeed share many similarities. We could conclude that both of these fall into the same genre of movies based on intuition, but that's no fun in a data science context. In this notebook, I have quantify the similarity of movies based on their plot summaries available on IMDb and Wikipedia, then separated them into groups, also known as clusters. Then created a dendrogram to represent how closely the movies are related to each other.</p>

