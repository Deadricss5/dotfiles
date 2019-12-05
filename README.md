# dotfiles for linux


### Hyper-V vs vSphere vs XenServer vs KVM
<table>
    <thead>
        <tr>
            <th>Feature</th>
            <th>Windows Hyper-V 2019</th>
            <th>vSphere 6.7</th>
            <th>XenServer 7.6	</th>
            <th>KVM</th>
        </tr>
    </thead>
    <tbody>
    <tr>
    <td> RAM/Host	</td>
    <td> 24TB</td>
    <td> 12 TB	</td>
    <td> 5TB	</td>
    <td> 12TB </td>
    </tr>
        <tr>
        <td rowspan=3>RAM/VM</td>
         <td >12 TB for generation 2;	</td>
         <td rowspan=3>6 TB		</td>
        <td rowspan=3>1.5TB	</td>
        <td rowspan=3>6 TB</td>
        </tr>
        <tr>
        </tr>
        <tr>
            <td>1 TB for generation 1	</td>
        </tr>
        <tr>
            <td rowspan=3>CPUs/VM	</td>
            <td>240 for generation 2;</td>
            <td rowspan=3>128</td>
            <td rowspan=3>32</td>
            <td rowspan=3>240</td>
        </tr>
        <tr>
        </tr>
        <tr>
            <td>64 for generation 1;</td>
        </tr>
                <tr>
            <td rowspan=3>VM Disk	</td>
            <td>64 TB for VHDX format;	</td>
            <td rowspan=3>62TB</td>
            <td rowspan=3>2TB</td>
            <td rowspan=3>10TB</td>
        </tr>
        <tr>
        </tr>
        <tr>
            <td>2040 GB for VHD format</td>
        </tr>
        <tr>
        <td>VM Live Migration	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        </tr>
                <tr>
        <td>VM Replication supports	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        </tr>
                <tr>
        <td>Overcommit resources	</td>
        <td>No	</td>
        <td>Yes	</td>
        <td>No	</td>
        <td>Yes	</td>
        </tr>
                <tr>
        <td>Disk I/O Throttling	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        </tr>
                <tr>
        <td>Hot plug of virtual resources	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        </tr>
    </tbody>
</table>