<h1>Display KML Network Links</h1>

<p>KML files can reference other KML files on the network as well as refresh intervals. This can be used to create a map that will periodically refresh itself with the latest data. This sample demonstrates how to display a file with a network link.
</p>

<p><img src="Displaykmlnetworklinks.png"/></p>

<h2>How to use the sample</h2>

<p>The data shown should refresh automatically every few seconds. A network message will be displayed when the dataset is loaded.</p>

<h2>How it works</h2>

<p>To show KML with network links and display network messages:</p>

<ol>
    <li>Create a <code>KmlDataset</code> from a KML source which has network links.</li>
    <li>Construct a <code>KmlLayer</code> with the dataset and add the layer as an operational layer.</li>
    <li>To listen for network messages, add a <code>KmlNetworkLinkMessageReceivedListener</code> on the dataset.</li>
</ol>

<h2>Relevant API</h2>

<ul>
<li>KmlDataset</li>
<li>KmlLayer</li>
<li>KmlNetworkLinkMessageReceivedEvent</li>
</ul>

<h2>About the data</h2>

<p>This map shows the current air traffic in parts of Europe with heading, altitude, and ground speed. Additionally, noise levels from ground monitoring stations are shown.</p>

<h2>Tags</h2>

<p>KML, KMZ, OGC, Keyhole, Network Link, Network Link Control</p>