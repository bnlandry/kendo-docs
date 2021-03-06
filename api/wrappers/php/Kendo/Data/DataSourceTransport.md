---
title: DataSourceTransport
slug: php-data-datasourcetransport
tags: api, php
publish: true
---

# \Kendo\Data\DataSourceTransport

A PHP class representing the transport setting of DataSource.


## Methods

### create

Options for remote create data operation, or the URL of the remote service.

#### Returns
`\Kendo\Data\DataSourceTransport`

#### Parameters

##### $value `string|\Kendo\JavaScriptFunction|\Kendo\Data\DataSourceTransportCreate|array`




#### Example  - using string
    <?php
    $transport = new \Kendo\Data\DataSourceTransport();
    $transport->create('value');
    ?>

#### Example  - using \Kendo\JavaScriptFunction
    <?php
    $transport = new \Kendo\Data\DataSourceTransport();
    $transport->create(new \Kendo\JavaScriptFunction('function() { }'));
    ?>


#### Example - using [\Kendo\Data\DataSourceTransportCreate](/api/wrappers/php/Kendo/Data/DataSourceTransportCreate)
    <?php
    $transport = new \Kendo\Data\DataSourceTransport();
    $create = new \Kendo\Data\DataSourceTransportCreate();
    $cache = true;
    $create->cache($cache);
    $transport->create($create);
    ?>

#### Example - using array

    <?php
    $transport = new \Kendo\Data\DataSourceTransport();
    $cache = true;
    $transport->create(array('cache' => $cache));
    ?>

### destroy

Options for remote destroy data operation, or the URL of the remote service.

#### Returns
`\Kendo\Data\DataSourceTransport`

#### Parameters

##### $value `string|\Kendo\JavaScriptFunction|\Kendo\Data\DataSourceTransportDestroy|array`




#### Example  - using string
    <?php
    $transport = new \Kendo\Data\DataSourceTransport();
    $transport->destroy('value');
    ?>

#### Example  - using \Kendo\JavaScriptFunction
    <?php
    $transport = new \Kendo\Data\DataSourceTransport();
    $transport->destroy(new \Kendo\JavaScriptFunction('function() { }'));
    ?>


#### Example - using [\Kendo\Data\DataSourceTransportDestroy](/api/wrappers/php/Kendo/Data/DataSourceTransportDestroy)
    <?php
    $transport = new \Kendo\Data\DataSourceTransport();
    $destroy = new \Kendo\Data\DataSourceTransportDestroy();
    $cache = true;
    $destroy->cache($cache);
    $transport->destroy($destroy);
    ?>

#### Example - using array

    <?php
    $transport = new \Kendo\Data\DataSourceTransport();
    $cache = true;
    $transport->destroy(array('cache' => $cache));
    ?>

### parameterMap
Converts the request parameters and data from the internal format to a format suitable for the remote service.

#### Returns
`\Kendo\Data\DataSourceTransport`

#### Parameters

##### $value `\Kendo\JavaScriptFunction`



#### Example 
    <?php
    $transport = new \Kendo\Data\DataSourceTransport();
    $transport->parameterMap(new \Kendo\JavaScriptFunction('function() { }'));
    ?>

### read

Options for remote read data operation, or the URL of the remote service.

#### Returns
`\Kendo\Data\DataSourceTransport`

#### Parameters

##### $value `string|\Kendo\JavaScriptFunction|\Kendo\Data\DataSourceTransportRead|array`




#### Example  - using string
    <?php
    $transport = new \Kendo\Data\DataSourceTransport();
    $transport->read('value');
    ?>

#### Example  - using \Kendo\JavaScriptFunction
    <?php
    $transport = new \Kendo\Data\DataSourceTransport();
    $transport->read(new \Kendo\JavaScriptFunction('function() { }'));
    ?>


#### Example - using [\Kendo\Data\DataSourceTransportRead](/api/wrappers/php/Kendo/Data/DataSourceTransportRead)
    <?php
    $transport = new \Kendo\Data\DataSourceTransport();
    $read = new \Kendo\Data\DataSourceTransportRead();
    $cache = true;
    $read->cache($cache);
    $transport->read($read);
    ?>

#### Example - using array

    <?php
    $transport = new \Kendo\Data\DataSourceTransport();
    $cache = true;
    $transport->read(array('cache' => $cache));
    ?>

### update

Options for remote update data operation, or the URL of the remote service.

#### Returns
`\Kendo\Data\DataSourceTransport`

#### Parameters

##### $value `string|\Kendo\JavaScriptFunction|\Kendo\Data\DataSourceTransportUpdate|array`




#### Example  - using string
    <?php
    $transport = new \Kendo\Data\DataSourceTransport();
    $transport->update('value');
    ?>

#### Example  - using \Kendo\JavaScriptFunction
    <?php
    $transport = new \Kendo\Data\DataSourceTransport();
    $transport->update(new \Kendo\JavaScriptFunction('function() { }'));
    ?>


#### Example - using [\Kendo\Data\DataSourceTransportUpdate](/api/wrappers/php/Kendo/Data/DataSourceTransportUpdate)
    <?php
    $transport = new \Kendo\Data\DataSourceTransport();
    $update = new \Kendo\Data\DataSourceTransportUpdate();
    $cache = true;
    $update->cache($cache);
    $transport->update($update);
    ?>

#### Example - using array

    <?php
    $transport = new \Kendo\Data\DataSourceTransport();
    $cache = true;
    $transport->update(array('cache' => $cache));
    ?>

