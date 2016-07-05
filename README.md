# Elasticsearch Vagrant 

Assuming you have vagrant and virtualbox provider installed

1. clone project
2. run "vagrant up"
3. done

After installation run

    $ curl -X GET localhost:9200
    {
      "name" : "Vincente",
      "cluster_name" : "elasticsearch",
      "version" : {
        "number" : "2.3.3",
        "build_hash" : "218bdf10790eef486ff2c41a3df5cfa32dadcfde",
        "build_timestamp" : "2016-05-17T15:40:04Z",
        "build_snapshot" : false,
        "lucene_version" : "5.5.0"
      },
      "tagline" : "You Know, for Search"
    }
