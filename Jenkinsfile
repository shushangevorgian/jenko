import jenkins.model.*
//Groovy script to add a label to all slave nodes having labels matching a certain specification.

for (slave in jenkins.model.Jenkins.instance.slaves) {
    oldLabelName = slave.getLabelString()

    if (oldLabelName.contains('WIN2012')) {

        newLabelName = oldLabelName + " " + "WIN2012.X"
        slave.setLabelString(newLabelName)
    }
}
