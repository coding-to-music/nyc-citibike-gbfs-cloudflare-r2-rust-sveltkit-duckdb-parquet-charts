# nyc-citibike-gbfs-cloudflare-r2-rust-sveltkit-duckdb-parquet-charts

# 🚀 nyc-citibike-gbfs-cloudflare-r2-rust-sveltkit-duckdb-parquet-charts 🚀

There are three sub-projects in this repository:

- web, the DuckDB and SvelteKit-based frontend
- collector, the Rust-based tool that parses and compresses ride data into Parquet files
- worker, the script that requests the latest station_status information every five minutes and stores it in R2

https://github.com/coding-to-music/nyc-citibike-gbfs-cloudflare-r2-rust-sveltkit-duckdb-parquet-charts

https://nyc-citibike-gbfs-cloudflare-r2-rust-sveltkit-duckdb-parquet-charts.vercel.app

From / By https://github.com/tmcw/bikesharecharts

https://bikesharecharts.com/

https://macwright.com/2023/09/17/bikeshare-1

https://observablehq.com/@tmcw/bikeshare-charts

<!-- <div style="text-align:center;">
  <img src="/images/chakra.jpg" alt="Image" />
  <p><em>Chakra Component Library with Next.js</em></p>
</div> -->

## Node Version:

```java
nvm use 18

Now using node v18.17.1 (npm v10.1.0)
```

## Environment variables:

```java

```

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/nyc-citibike-gbfs-cloudflare-r2-rust-sveltkit-duckdb-parquet-charts.git
git push -u origin main
```

# bikesharecharts

This is a project to look closely at bikeshare data, initially
in New York City, and see what we can find. I use the Citibike
system constantly, and notice all kinds of trends: fluctuating
ratios of electric to non-electric bicycles or certain docks that
are always full. The system is run by Lyft, which is [not
doing very well as a business](https://www.curbed.com/2023/04/lyft-bike-share-citi-bike.html), so the
system could transition to another company in the near future.

This is also a good opportunity to try out some new technology, like DuckDB
and Parquet. This project uses Parquet as a data format for the rides,
and DuckDB to load that data into a fast SQL database and drive the frontend.

There are three sub-projects in this repository:

- web, the DuckDB and SvelteKit-based frontend
- collector, the Rust-based tool that parses and compresses ride data into Parquet files
- worker, the script that requests the latest station_status information every five minutes and stores it in R2

---

This project is a very early work in progress, and something I'm
doing in my limited free time. If you want to contribute on an
existing issue or propose something that you might want to do,
go for it! I'd love to collaborate with folks.
