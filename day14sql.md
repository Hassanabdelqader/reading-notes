# SQL database, ORM, Sequelize

## Review, Research, and Discussion

### What's the difference between SQL  and NoSQL?




```
   SQL : Relational Databases (RDBMS) and table based databases and 
    predefined schema dynamic schema for unstructured datauses SQL ( structured query language ) for defining and manipulating the data 
    NO-SQL : non-relational or distributed database and document based, key-value pairs, graph databases or wide-column stores
    queries are focused on collection of documents. Sometimes it is also called as UnQL (Unstructured Query Language).
```
### What is Sequlize and how to use it with Node js?

- a modern TypeScript and Node.js ORM for Postgres, MySQL, MariaDB, SQLite and SQL Server

```bash
npm install pg sequelize // install 
sqlstart
```

```const Wishlist = sequelize.define("Wishlist", {
  title: DataTypes.STRING,
});
const Wish = sequelize.define("Wish", {
  title: DataTypes.STRING,
  quantity: DataTypes.NUMBER,
});

// Automatically create all tables
await sequelize.sync();
```

#### for more info checkout [How to use Sequelize to interact with PostgreSQL](https://flaviocopes.com/sequelize/)

<br/>

### What is an ORM, how does it work, and how should I use one?

- Object-Relational Mapping

> ORM resolves the object code and relational database mismatch with three approaches: bottom up, top-down and meet in the middle. Each approach has its share of benefits and drawbacks. When selecting the best software solution, developers must fully understand the environment and design requirements.
> In addition to the data access technique, ORM's benefits also include:
>
>> Simplified development because it automates object-to-table and table-to-object conversion, resulting in lower development and maintenance costs
>>
>> Less code compared to embedded SQL and handwritten stored procedures
>>
>> Transparent object caching in the application tier, improving system performance
>>
>> An optimized solution making an application faster and easier to maintain
>>
> ORM’s emergence in multiple application development has created disagreement among experts. Key concerns are that ORM does not perform well and that stored procedures might be a better solution. In addition, ORM dependence may result in poorly-designed databases in certain circumstances.

#### for more info checkout [Object-Relational Mapping (ORM)](https://www.techopedia.com/definition/24200/object-relational-mapping--orm)

<br/>

### Document the following Vocabulary Terms

- SQL
- NoSQL
- Database schema
- WRRC

## Preview

### Which 3 things had you heard about previously and now have better clarity on?

- ORM
- No SQL 
- SQL databases

### Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

- No-SQL
- Postgresql
- ORM
- SQL databases

### What are you most excited about trying to implement or see how it works?

- ORM 

## Preparation Materials

- [SQL database](https://www.techtarget.com/searchdatamanagement/definition/SQL)
- [Sequelize](https://sequelize.org/)
- [ORM](https://www.techopedia.com/definition/24200/object-relational-mapping--orm)
- [CRUD system](https://zellwk.com/blog/crud-express-mongodb/)
