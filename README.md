### How to Setup Snowflake, DBT, GitHub Workflow

- Setup a free snowflake account, dbt account, and GitHUb account
- In snowflake, create the warehouse, databases, schema and tables in a snowflake worksheet with admin privileges
- Load data into tables using public S3 csv files
- 


### Issues to be aware of
  The most difficult part of this tutorial, without a doubt, is getting dbt to connect to snowflake. There are 
about 8 ways to make a mistake on this step. Make sure for the account field, that you include the cloudplatform you 
are using, (.west-us-2.azure in my case). Also, make sure the dev credentials you input are your snowflake credentials, 
not your dbt login. Keep in mind, you load data into the Raw database, but you connect DBT to the Analytics database. 


### Resources:
- [Youtube tutorial](https://www.youtube.com/watch?v=pzBf4KEvrUQ)
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [dbt community](http://community.getbdt.com/) to learn from other analytics engineers
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices
