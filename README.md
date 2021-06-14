/*

    ### xmlAssets.js has multiple indices for objects.

      * These need to be fufilled to add an object.

      > id: unique stripped to plain text [<b>indexed</b>]

      > title: unique nine digit numerical [<b>indexed</b>]

      > des: plain text [indexed].

      > cat: translations

      > uri: endpoint used in xmlRequestParsing in xmlFunctions.js

      > hash: unique two char alphanumeric indexed by init.js [indexed]

      > media: feed contains images boolean indexed by onlyImages.


       [indexed] filtered by response in baseFunctions.js

       *** Youtube uri
       userName: https://www.youtube.com/feeds/videos.xml?user=
       channel: https://www.youtube.com/feeds/videos.xml?channel_id=

*/
