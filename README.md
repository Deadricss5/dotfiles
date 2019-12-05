# dotfiles
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
    <tr style='backgroundcolor: white'>
    <td> RAM/Host	</td>
    <td> 24TB</td>
    <td> 12 TB	</td>
    <td> 5TB	</td>
    <td> 12TB </td>
    </tr>
        <tr style='backgroundcolor: white'>
        <td rowspan=2>RAM/VM</td>
         <td >12 TB for generation 2;	</td>
         <td rowspan=2>6 TB		</td>
        <td rowspan=2>1.5TB	</td>
        <td rowspan=2>6 TB</td>
        </tr>
        <tr style='backgroundcolor: white'>
            <td>1 TB for generation 1	</td>
        </tr>
        <tr style='backgroundcolor: white'>
            <td rowspan=2>CPUs/VM	</td>
            <td>240 for generation 2;</td>
            <td rowspan=2>128</td>
            <td rowspan=2>32</td>
            <td rowspan=2>240</td>
        </tr>
        <tr style='backgroundcolor: white'>
            <td>64 for generation 1;</td>
        </tr>
                <tr style='backgroundcolor: white'>
            <td rowspan=2>VM Disk	</td>
            <td>64 TB for VHDX format;	</td>
            <td rowspan=2>62TB</td>
            <td rowspan=2>2TB</td>
            <td rowspan=2>10TB</td>
        </tr>
        <tr style='backgroundcolor: white'>
            <td>2040 GB for VHD format</td>
        </tr>
        <tr style='backgroundcolor: white'>
        <td>VM Live Migration	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        </tr>
                <tr style='backgroundcolor: white'>
        <td>VM Replication supports	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        </tr>
                <tr style='backgroundcolor: white'>
        <td>Overcommit resources	</td>
        <td>No	</td>
        <td>Yes	</td>
        <td>No	</td>
        <td>Yes	</td>
        </tr>
                <tr style='backgroundcolor: white'>
        <td>Disk I/O Throttling	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        </tr>
                <tr style='backgroundcolor : white'></tr>
        <td>Hot plug of virtual resources	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        <td>Yes	</td>
        </tr>