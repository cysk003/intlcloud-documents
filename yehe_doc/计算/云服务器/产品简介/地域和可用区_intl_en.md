## Regions

### Introduction

A region is the physical location of an IDC. In Tencent Cloud, regions are fully isolated from each other, ensuring cross-region stability and fault tolerance. When purchasing Tencent Cloud services, we recommend selecting the region closest to your end users to minimize access latency and improve download speed.

You can view the following table or use the [DescribeRegions](https://www.tencentcloud.com/document/product/213/15708) API to get a complete list of regions.

### Characteristics

- The networks of different regions are fully isolated. Tencent Cloud services in different regions **cannot communicate via a private network by default**.
- Tencent Cloud services across regions can communicate with each other through public IPs as instructed in [Internet Access](https://intl.cloud.tencent.com/document/product/213/5224), while those in different VPCs can communicate with each other through [Cloud Connect Network](https://www.tencentcloud.com/document/product/1003) that is faster and steadier.
- [Cloud Load Balancer (CLB)](https://www.tencentcloud.com/document/product/214) currently supports intra-region traffic forwarding by default. If you enable the [cross-region binding](https://www.tencentcloud.com/document/product/214/38441) feature, a CLB instance can be bound to CVM instances in another region.

## Availability Zones

### Introduction

An availability zone (AZ) is a physical IDC of Tencent Cloud with independent power supply and network in the same region. It can ensure business stability, as failures (except for major disasters or power failures) in one AZ are isolated without affecting other AZs in the same region. By starting an instance in an independent AZ, users can protect their applications from being affected by a single point of failure.
You can view the following table or use the [DescribeZones](https://www.tencentcloud.com/document/product/213/35071) API to get a complete list of availability zones.

### Characteristics

Tencent Cloud products that are in the same region, different availability zones, and the same VPC are interconnected through the private network. They can be accessed directly through [private IP addresses](https://www.tencentcloud.com/document/product/213/5225).
<dx-alert infotype="explain" title="">
Private network interconnection refers to the interconnection of resources under the same account. Resources under different accounts are completely isolated on the private network.
</dx-alert>


## Mainland China[](id:MainlandChina)
<table class="table-striped">
<tbody>
	<tr>
		<th>Region</th>
		<th>AZ</th>
	</tr>
	<tr>
		<td rowspan="6">South China (Guangzhou)<br> ap-guangzhou</td>
		<td>Guangzhou Zone 1 (sold out)<br> ap-guangzhou-1</td>
	</tr>	
	<tr>
		<td>Guangzhou Zone 2 (sold out)<br>ap-guangzhou-2</td>
	</tr>
	<tr>
		<td>Guangzhou Zone 3<br> ap-guangzhou-3</td>
	</tr>
	<tr>
		<td>Guangzhou Zone 4</br>ap-guangzhou-4</td>
	</tr>
	<tr>
		<td>Guangzhou Zone 6<br>ap-guangzhou-6</td>
	</tr>
	<tr>
		<td>Guangzhou Zone 7<br>ap-guangzhou-7</td>
	</tr>
	<tr>
		<td rowspan="6">East China (Shanghai)<br>ap-shanghai</td>
		<td>Shanghai Zone 1 (sold out)<br>ap-shanghai-1</td>
	</tr>
	<tr>
		<td>Shanghai Zone 2</br>ap-shanghai-2</td>
	</tr>
	<tr>
		<td>Shanghai Zone 3</br>ap-shanghai-3</td>
	</tr>
	<tr>
		<td>Shanghai Zone 4<br>ap-shanghai-4</td>
	</tr>
 <tr>
		<td>Shanghai Zone 5<br>ap-shanghai-5</td>
	</tr>
	 <tr>
		<td>Shanghai Zone 8<br>ap-shanghai-8</td>
	</tr>
	<tr>
			<td rowspan="3">East China (Nanjing)<br>ap-nanjing</td>
			<td>Nanjing Zone 1<br>ap-nanjing-1</td>
	</tr>
	<tr>
			<td>Nanjing Zone 2<br>ap-nanjing-2</td>
	</tr>
	<tr>
			<td>Nanjing Zone 3<br>ap-nanjing-3</td>
	</tr>
	<tr>
			<td rowspan="7">North China (Beijing)<br>ap-beijing</td>
			<td>Beijing Zone 1 (sold out)<br>ap-beijing-1</td>
	</tr>
	<tr>
			<td>Beijing Zone 2</br>ap-beijing-2</td>
	</tr>
	<tr>
			<td>Beijing Zone 3</br>ap-beijing-3</td>
	</tr>
	<tr>
			<td>Beijing Zone 4<br>ap-beijing-4</td>
	</tr>
	<tr>
			<td>Beijing Zone 5<br>ap-beijing-5</td>
	</tr>
		<tr>
			<td>Beijing Zone 6<br>ap-beijing-6</td>
	</tr>
		<tr>
			<td>Beijing Zone 7<br>ap-beijing-7</td>
	</tr>
	<tr>
		<td rowspan="2">Southwest China (Chengdu)<br>ap-chengdu</td>
		<td>Chengdu Zone 1<br>ap-chengdu-1</td>
	</tr>
	<tr>
			<td>Chengdu Zone 2</br>ap-chengdu-2</td>
	</tr>    
	<tr>
			<td>Southwest China (Chongqing)<br>ap-chongqing</td>
			<td>Chongqing Zone 1<br>ap-chongqing-1</td>
	</tr>
	<tr>
			<td rowspan="3">Hong Kong/Macao/Taiwan (Hong Kong, China)<br>ap-hongkong</td>
			<td>Hong Kong Zone 1 (Nodes in Hong Kong, China can cover Hong Kong/Macao/Taiwan regions) <br>ap-hongkong-1</td>
	</tr>
	<tr>
			<td>Hong Kong Zone 2 (Nodes in Hong Kong, China can cover services in Hong Kong/Macao/Taiwan regions)<br>ap-hongkong-2</td>
	</tr>
	<tr>
			<td>Hong Kong Zone 3 (Nodes in Hong Kong, China can cover Hong Kong/Macao/Taiwan regions)<br>ap-hongkong-3</td>
	</tr>
</tbody>
</table>	

<dx-alert infotype="explain" title="">
The product is in beta test for Jinan, Hangzhou, Fuzhou, Wuhan, Changsha, and Shijiazhuang regions. To try it out, contact the sales rep for application.
</dx-alert>


## Other countries and regions[](id:InternationalArea)	
<table class="table-striped">
	<tbody>
	<tr>
			<th>Region</th>
			<th>AZ</th>
		</tr>
		<tr>
			<td  rowspan="4">Southeast Asia (Singapore)<br>ap-singapore</td>
			<td>Singapore Zone 1 (Nodes in Singapore can cover Southeast Asia)<br>ap-singapore-1</td>
		</tr>
		<tr>
			<td>Singapore Zone 2 (Nodes in Singapore can cover Southeast Asia)<br>ap-singapore-2</td>
		</tr>
		<tr>
			<td>Singapore Zone 3 (Nodes in Singapore can cover Southeast Asia)<br>ap-singapore-3</td>
		</tr>
   <tr>
			<td>Singapore Zone 4 (Nodes in Singapore can cover Southeast Asia)<br>ap-singapore-4</td>
		</tr>
		<tr>
			<td rowspan="2">Southeast Asia (Jakarta)<br>ap-jakarta</td>
			<td>Jakarta Zone 1 (Nodes in Jakarta can cover Southeast Asia)<br>ap-jakarta-1</td>
		</tr>
		<tr>
			<td>Jakarta Zone 2 (Nodes in Jakarta can cover Southeast Asia)<br>ap-jakarta-2</td>
		</tr>
		<tr>
			<td  rowspan="2">Northeast Asia (Seoul)<br>ap-seoul</td>
			<td>Seoul Zone 1 (Nodes in Seoul can cover Northeast Asia)<br>ap-seoul-1</td>
		</tr>
		<tr>
			<td>Seoul Zone 2 (Nodes in Seoul can cover Northeast Asia)<br>ap-seoul-2</td>
		</tr>
		<tr>
			<td rowspan="2">Northeast Asia (Tokyo)<br>ap-tokyo</td>
			<td>Tokyo Zone 1 (Nodes in Tokyo can cover Northeast Asia)<br>ap-tokyo-1</td>
		</tr>
		 <tr>
			<td>Tokyo Zone 2 (Tokyo nodes can cover services in Northeast Asia)<br>ap-tokyo-2</td>
		</tr>
       <tr>
			<td  rowspan="2">South Asia (Mumbai)<br>ap-mumbai</td>
			<td>Mumbai Zone 1 (Nodes in Mumbai can cover South Asia)<br>ap-mumbai-1</td>
		</tr>
       <tr>
			<td>Mumbai Zone 2 (Nodes in Mumbai can cover South Asia) <br>ap-mumbai-2</td>
		</tr>
		<tr>
		  	<td rowspan="2">Southeast Asia (Bangkok)<br>ap-bangkok</td>
				 <td>Bangkok Zone 1 (Nodes in Bangkok can cover Southeast Asia)<br>ap-bangkok-1</td>
		</tr>
		<tr>
			<td>Bangkok Zone 2 (Nodes in Bangkok can cover Southeast Asia)<br>ap-bangkok-2</td>
		</tr>
		<tr>
			<td>North America (Toronto)<br>na-toronto</td>
			<td>Toronto Zone 1 (Nodes in Toronto can cover North America)<br>na-toronto-1</td>
		</tr>
		<tr>
			<td>South America (São Paulo)<br>sa-saopaulo</td>
			<td>Sao Paulo Zone 1 (Sao Paulo nodes cover services in South America)<br>sa-saopaulo-1</td>
		</tr>
		<tr>
			<td rowspan="2">West US (Silicon Valley)<br>na-siliconvalley</td>
			<td>Silicon Valley Zone 1 (Nodes in Silicon Valley can cover Western US)<br>na-siliconvalley-1</td>
		</tr>
    <tr>
			<td>Silicon Valley Zone 2 (Nodes in Silicon Valley can cover Western US)<br>na-siliconvalley-2</td>
		</tr>
		<tr>
			<td rowspan="2">East US (Virginia)<br>na-ashburn</td>
			<td>Virginia Zone 1 (Nodes in Virginia can cover Eastern US)<br>na-ashburn-1</td>
		</tr>
		<tr>
			<td>Virginia Zone 2 (Nodes in Virginia can cover Eastern US)<br>na-ashburn-2</td>
		</tr>
		<tr>
			<td rowspan="2">Europe (Frankfurt)<br>eu-frankfurt</td>
			<td>Frankfurt Zone 1 (Nodes in Frankfurt can cover Europe)<br>eu-frankfurt-1</td>
		</tr>
		<tr>
			<td>Frankfurt Zone 2 (Nodes in Frankfurt can cover Europe)<br>eu-frankfurt-2</td>
		</tr>
	</tbody>
</table>

## Regions and AZ Selection

When selecting a region and AZ, take the following into consideration:
- Your location, the location of your users, and the region of the CVM instances.
We recommend that you choose the region closest to your end users when purchasing CVM instances to minimize access latency and improve access speed.
- Other Tencent Cloud services you use.
When you select other Tencent Cloud services, we recommend that you try to locate them all in the same region and AZ to allow them to communicate with each other through the private network, reducing access latency and increasing access speed.
- High availability and disaster recovery.
Even if you have just one VPC, we still recommend that you deploy your businesses in different availability zones to prevent a single point of failure and enable cross-AZ disaster recovery.
- There may be network latency among different AZs. We recommend you assess your business requirements and find the optimal balance between high availability and low latency.
- If you need access to CVM instances in other countries or regions, we recommend you select a CVM in those other countries or regions. If you use a CVM instance in [China](#MainlandChina) to access [servers in other countries and regions](#InternationalArea), you may encounter much higher network latency.

## Resource Availability
The following table describes which Tencent Cloud resources are global, which are regional, and which are specific to availability zones.

<table>
	<tr><th width="14%">Resource</th><th>Resource ID Format<br><Resource Abbreviation>-8-Digit String of Numbers and Letters</th><th>Type</th><th>Description</th></tr>
	<tbody>
	<tr>
	  <td>User Account</td>
	  <td>No limit</td>
	  <td>Globally unique</td>
	  <td>Users can use the same account to access Tencent Cloud resources around the world.</td>
	</tr>
	<tr>
	<td> <a href="https://www.tencentcloud.com/document/product/213/6092">SSH Keys</a> </td>
	  <td>skey-xxxxxxxx</td>
	  <td>Global</td>
	  <td>Users can use an SSH key to bind a CVM in any region under the account.</td>
	</tr>
	<tr>
	<td> <a href="https://www.tencentcloud.com/document/product/213/4939">CVM Instances</a> </td>
	  <td>ins-xxxxxxxx</td>
	  <td>Instances are AZ-specific.</td>
	  <td>Users can only create a CVM instance in a specific AZ.</td>
	</tr>
	<tr>
	<td> <a href="https://www.tencentcloud.com/document/product/213/4941">Custom Images</a> </td>
	  <td>img-xxxxxxxx</td>
	  <td>Available in multiple availability zones of a region</td>
	  <td>Custom images created for the instance are available to all availability zones of the same region. Use <b>Copy Image</b> to copy a custom image if you need to use it in other regions.</td>
	</tr>
	<tr>
	<td> <a href="https://www.tencentcloud.com/document/product/213/5733">Elastic IPs</a> </td>
	  <td>eip-xxxxxxxx</td>
	  <td>Available in multiple availability zones of a region</td>
	  <td>EIPs are region-specific and can only be associated with instances in the same region.</td>
	</tr>
	<tr>
	<td> <a href="https://www.tencentcloud.com/document/product/213/12452">Security Group</a> </td>
	  <td>sg-xxxxxxxx</td>
	  <td>Available in multiple availability zones of a region</td>
	  <td>Security groups can only be associated with instances in the same region. Tencent Cloud automatically creates three default security groups for users.</td>
	</tr>
	<tr>
	<td><a href="https://www.tencentcloud.com/document/product/213/4953">Cloud Block Storage</a></td>
	  <td>disk-xxxxxxxx</td>
	  <td>Instances are AZ-specific.</td>
	  <td>Users can only create a Cloud Block Storage disk in a specific AZ and attach it to instances in the same availability zone.</td>
	</tr>
	<tr>
	<td> <a href="https://www.tencentcloud.com/document/product/362/31638">Snapshots</a> </td>
	  <td>snap-xxxxxxxx</td>
	  <td>Available in multiple availability zones of a region</td>
	  <td>A snapshot created from a cloud disk can be used for other purposes (such as creating cloud disks) in this region.</td>
	</tr>
	<tr>
	<td> <a href="https://www.tencentcloud.com/document/product/214/524">Cloud Load Balancer</a> </td>
	  <td>clb-xxxxxxxx</td>
	  <td>Available in multiple availability zones of a region</td>
	  <td>Cloud Load Balancer can be bound with CVMs in different availability zones of a single region for traffic forwarding.</td>
	</tr>
	<tr>
	<td> <a href="https://www.tencentcloud.com/document/product/215/535">VPC</a> </td>
	  <td>vpc-xxxxxxxx</td>
	  <td>Available in multiple availability zones of a region</td>
	  <td>A VPC in one region can have resources created in different availability zones of the region.</td>
	</tr>
	<tr>
	<td> <a href="https://www.tencentcloud.com/document/product/215/535#.E5.AD.90.E7.BD.91">Subnets</a> </td>
	  <td>subnet-xxxxxxxx</td>
	  <td>Instances are AZ-specific.</td>
	  <td>Users cannot create subnets across availability zones.</td>
	</tr>
	<tr>
	<td> <a href="https://www.tencentcloud.com/document/product/215/31810">Route Tables</a> </td>
	  <td>rtb-xxxxxxxx</td>
	  <td>Available in multiple availability zones of a region</td>
	  <td>When creating a route table, users need to specify a VPC. Therefore, route tables are regional as well.</td>
	</tr>
	</tbody>
</table>


## Relevant Operations

### Migrating an instance to another availability zone

Once launched, an instance cannot be migrated to another availability zone. However, you can create a custom image of the CVM instance and use the image to launch or update an instance in a different availability zone.
1. Create a custom image for the current instance. For more information, see [Create Custom Images](https://www.tencentcloud.com/document/product/213/4942).
2. If the instance is on a VPC [network environment](https://www.tencentcloud.com/document/product/213/5227) and you want to retain its current private IP address after the migration, first delete the subnet in the current availability zone and then create a subnet in the new availability zone with the same IP address range. Note that a subnet can be deleted only when it contains no available instances. Therefore, all the instances in the current subnet should be migrated to the new subnet.
3. Create a new instance in the new availability zone by using the custom image you have just created. You can choose the same type and configuration as the original instance, or choose new settings. For more information, see [Creating Instances via CVM Purchase Page](https://www.tencentcloud.com/document/product/213/4855).
4. If an elastic IP is associated with the original instance, you need to dissociate it from the old instance and associate it with the new instance. For more information, see [Elastic IP](https://www.tencentcloud.com/document/product/213/5733).
5. (Optional) If the original instance is [pay-as-you-go](https://www.tencentcloud.com/document/product/213/2180), then you can choose to terminate the original instance. For more information, see [Terminate Instances](https://www.tencentcloud.com/document/product/213/4930).

### Copying images to other regions

Operations such as launching and viewing instances are region-specific. If the image of the instance that you need to launch does not exist in the region, the image needs to be copied to the desired region. For more information, see [Copying Images](https://www.tencentcloud.com/document/product/213/4943).

