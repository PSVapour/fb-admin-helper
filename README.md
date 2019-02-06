<a name="FirebaseAdminHelper"></a>

## FirebaseAdminHelper
A wrapper for Firebase Realtime Database Admin nodejs.

**Kind**: global class  

* [FirebaseAdminHelper](#FirebaseAdminHelper)
    * [new FirebaseAdminHelper(credential, dbURL)](#new_FirebaseAdminHelper_new)
    * [.get(location)](#FirebaseAdminHelper+get) ⇒ <code>Notifier</code>
    * [.last(location)](#FirebaseAdminHelper+last) ⇒ <code>Notifier</code>
    * [.updated(location)](#FirebaseAdminHelper+updated) ⇒ <code>Notifier</code>
    * [.added(location)](#FirebaseAdminHelper+added) ⇒ <code>Notifier</code>
    * [.removed(location)](#FirebaseAdminHelper+removed) ⇒ <code>Notifier</code>
    * [.value(location)](#FirebaseAdminHelper+value) ⇒ <code>Notifier</code>
    * [.push(location)](#FirebaseAdminHelper+push) ⇒ <code>Notifier</code>
    * [.pushEach(location)](#FirebaseAdminHelper+pushEach) ⇒ <code>Notifier</code>

<a name="new_FirebaseAdminHelper_new"></a>

### new FirebaseAdminHelper(credential, dbURL)
Initialise database with your firebase credentials.


| Param | Type | Description |
| --- | --- | --- |
| credential | <code>string</code> | Firebase admin serviceAccountKey |
| dbURL | <code>string</code> | Firebase database URL |

<a name="FirebaseAdminHelper+get"></a>

### firebaseAdminHelper.get(location) ⇒ <code>Notifier</code>
get will get all data store at the location proveded

**Kind**: instance method of [<code>FirebaseAdminHelper</code>](#FirebaseAdminHelper)  
**Returns**: <code>Notifier</code> - Notifier class  

| Param | Type | Description |
| --- | --- | --- |
| location | <code>string</code> | The location of the data |

<a name="FirebaseAdminHelper+last"></a>

### firebaseAdminHelper.last(location) ⇒ <code>Notifier</code>
get will get all data store at the location proveded

**Kind**: instance method of [<code>FirebaseAdminHelper</code>](#FirebaseAdminHelper)  
**Returns**: <code>Notifier</code> - Notifier class  

| Param | Type | Description |
| --- | --- | --- |
| location | <code>string</code> | The location of the data |

<a name="FirebaseAdminHelper+updated"></a>

### firebaseAdminHelper.updated(location) ⇒ <code>Notifier</code>
**Kind**: instance method of [<code>FirebaseAdminHelper</code>](#FirebaseAdminHelper)  
**Returns**: <code>Notifier</code> - new Notifier  

| Param | Type | Description |
| --- | --- | --- |
| location | <code>string</code> | The location of the data |

<a name="FirebaseAdminHelper+added"></a>

### firebaseAdminHelper.added(location) ⇒ <code>Notifier</code>
get will get all data store at the location proveded

**Kind**: instance method of [<code>FirebaseAdminHelper</code>](#FirebaseAdminHelper)  
**Returns**: <code>Notifier</code> - Notifier class  

| Param | Type | Description |
| --- | --- | --- |
| location | <code>string</code> | The location of the data |

<a name="FirebaseAdminHelper+removed"></a>

### firebaseAdminHelper.removed(location) ⇒ <code>Notifier</code>
get will get all data store at the location proveded

**Kind**: instance method of [<code>FirebaseAdminHelper</code>](#FirebaseAdminHelper)  
**Returns**: <code>Notifier</code> - Notifier class  

| Param | Type | Description |
| --- | --- | --- |
| location | <code>string</code> | The location of the data |

<a name="FirebaseAdminHelper+value"></a>

### firebaseAdminHelper.value(location) ⇒ <code>Notifier</code>
get will get all data store at the location proveded

**Kind**: instance method of [<code>FirebaseAdminHelper</code>](#FirebaseAdminHelper)  
**Returns**: <code>Notifier</code> - Notifier class  

| Param | Type | Description |
| --- | --- | --- |
| location | <code>string</code> | The location of the data |

<a name="FirebaseAdminHelper+push"></a>

### firebaseAdminHelper.push(location) ⇒ <code>Notifier</code>
get will get all data store at the location proveded

**Kind**: instance method of [<code>FirebaseAdminHelper</code>](#FirebaseAdminHelper)  
**Returns**: <code>Notifier</code> - Notifier class  

| Param | Type | Description |
| --- | --- | --- |
| location | <code>string</code> | The location of the data |

<a name="FirebaseAdminHelper+pushEach"></a>

### firebaseAdminHelper.pushEach(location) ⇒ <code>Notifier</code>
get will get all data store at the location proveded

**Kind**: instance method of [<code>FirebaseAdminHelper</code>](#FirebaseAdminHelper)  
**Returns**: <code>Notifier</code> - Notifier class  

| Param | Type | Description |
| --- | --- | --- |
| location | <code>string</code> | The location of the data |
